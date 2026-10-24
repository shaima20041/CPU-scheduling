CORE//CPU — CPU Scheduling Simulator

FILES
- index.html: complete self-contained website (HTML + CSS + JavaScript).

RUN IN VS CODE
1. Create a folder named cpu_scheduler_ui.
2. Save index.html in that folder.
3. Open the folder in Visual Studio Code.
4. Open index.html.
5. Either right-click and choose "Open with Live Server" (if the Live Server extension is installed),
   or open index.html directly in your browser.
6. Select an algorithm, edit AT / BT / Priority, and click Run Simulation.

ALGORITHMS
- FCFS
- SJF (non-preemptive)
- SRTF (preemptive SJF)
- Priority (non-preemptive; smaller number means higher priority)
- Round Robin (set a positive integer Time Quantum)

NOTE
This is a browser-based front end and simulator written in JavaScript. It does not execute the C++ program directly.
If your assignment specifically requires the C++ code to be the engine behind the web interface, a local backend/API is needed.
