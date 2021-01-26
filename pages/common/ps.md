# ps

> Information about running processes.

- List all running processes:

`ps aux`

- List all running processes including the full command string:

`ps auxww`

- Search for a process that matches a string:

`ps aux | grep {{string}}`

- List all processes of the current user in extra full format:

`ps --user $(id -u) -F`

- List all processes of the current user as a tree:

`ps --user $(id -u) f`

- Get the parent pid of a process:

`ps -o ppid= -p {{pid}}`

- Sort processes by memory consumption:

`ps --sort size`

- View all processes running on the system. The -e parameter specifies that all processes running on the system are displayed.The -f parameter extends the output,and search for a process that matches a string.

`ps -ef | grep {{string}}` 

- One really nice feature of GNU's long parameters is the forest parameter.It displays the hierarchy information of the process.

` ps --forest | grep {{string}}`