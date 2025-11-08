🧠 System Monitor Tool (C++)
📘 Project Description

The System Monitor Tool is a C++ application that provides real-time insights into system performance, similar to the Linux top command. It displays running processes, CPU load, and memory usage while allowing users to sort processes, terminate tasks, and auto-refresh system statistics. This project demonstrates strong understanding of Linux system programming, process management, and real-time data handling using the /proc filesystem and system calls.

🚀 Features

Display real-time CPU and memory usage

List all active processes with PID, CPU load, and memory usage

Sort processes by CPU or memory utilization

Kill or terminate processes directly from the tool

Auto-refresh feature to update data dynamically every few seconds

Lightweight, command-line-based interface

🗓️ Development Plan

Day 1: Design basic UI layout and gather system data using /proc files
Day 2: Display process list with CPU and memory usage
Day 3: Implement sorting functionality (CPU / Memory)
Day 4: Add process termination (kill command)
Day 5: Implement real-time data refresh and update mechanism

⚙️ Technologies Used

Language: C++ (C++17)

Platform: Linux / Unix

System Calls: fork, kill, opendir, readdir, getrusage, sleep

Libraries: <dirent.h>, <unistd.h>, <sys/types.h>, <signal.h>

Data Source: /proc filesystem

🧩 Installation and Execution
# Clone the repository
git clone https://github.com/your-username/system-monitor-cpp.git
cd system-monitor-cpp

# Compile (example for Day 5)
g++ -std=c++17 Day5.cpp -o sysmon

# Run the tool
./sysmon


Optional Parameters:

./sysmon --sort=cpu      # Sort by CPU usage
./sysmon --sort=mem      # Sort by memory usage
./sysmon --refresh=3     # Refresh every 3 seconds

🧪 Example Output
-------------------------------------------
 PID     CPU%     MEM%     COMMAND
-------------------------------------------
 1023     12.3     3.2     firefox
 2104      8.7     1.5     gnome-shell
 1207      2.3     0.9     bash
-------------------------------------------
Refreshing every 3 seconds...

📚 Learning Outcomes

Hands-on experience with Linux process monitoring

Understanding of /proc filesystem parsing

Use of system calls for process control

Implementation of real-time data visualization in C++

Improved skills in low-level system programming and performance analysis

🤝 Contributors

ANANYA RAY
2241018100
ITER SOA UNIVERSITY

📄 License

This project is licensed under the MIT License
.
