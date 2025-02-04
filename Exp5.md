Commands:
--ps:(process status)command is used to view running processes on a system.

![lab5 1](https://github.com/user-attachments/assets/0f2e0e7f-e474-4f04-ae39-c9bd093219ed)
ps aux	Shows all running processes with user details.

ps -e	Lists all processes.

ps -ef	Displays full details of all processes.

ps -u username	Shows processes for a specific user.

ps -p PID	Displays details of a process with a specific PID.


--top:top command provides a live view of system processes.

![lab5 2](https://github.com/user-attachments/assets/72ac5e63-ff90-46e6-8aae-11b221be6b05)

top -u username	Shows processes of a specific user.

top -p PID	Monitors a specific process.

top -n 5	Runs top for 5 updates and exits.

top -o %MEM	Sorts processes by memory usage.

q	Quit top.

k	Kill a process (requires PID).

r	Renice a process (change priority).

M	Sort by memory usage.



--kill:kill command is used to terminate a process by its PID.

![lab5 3](https://github.com/user-attachments/assets/9cbdf825-d7b5-490a-b22a-1ab7bbc32f50)

kill -9 PID	Force kill a process (SIGKILL).

kill -15 PID	Gracefully terminate a process (SIGTERM).

killall process_name	Kills all instances of a process.

pkill process_name	Kills a process by name instead of PID.

--kill -9 PID:(used to kill forcefully)

![lab5 4](https://github.com/user-attachments/assets/90ec22ab-36e9-4f77-ab45-a02164c64106)


--sudo apt-get install package_name:for installation

![lab5 5](https://github.com/user-attachments/assets/02305d47-85df-49bf-a898-4c97b757afa0)

--sudo apt-get update:(for updating)

![lab5 6](https://github.com/user-attachments/assets/c87e0571-0bdc-4bf6-80bf-28df3e5ea356)


--sudo apt-get remove package_name:(remove the package)

![lab5 7](https://github.com/user-attachments/assets/0d5003b7-5f7b-49fb-a107-6a2e90862e02)
