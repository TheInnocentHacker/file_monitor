# file_monitor

file_monitor.py is a simple directory monitoring & reverse engineering program. file_monitor.py gives information about all files that is created,modified,renamed or deleted from the directory, as well as it will dump all the content from the file.

You can monitor any directory by just passing it as a parameter with '-p' switch or it will just start monitoring default temporary directories.

# Usage:
Directly call file_monitor.py which will start monitoring temporary directories of windows, 

like C:\WINDOWS\Temp, C:\Users\vaibhav\AppData\Local\Temp.

or 

You can give your own directory to monitor:

file_monitor.py  -p  C:\Users\vaibhav\Downloads, C:\Users
# Note:
You will need pywin32 for this program. You can install it using command:

pip install pywin32
