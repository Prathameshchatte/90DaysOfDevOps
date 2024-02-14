blog link = https://prathameshchatte.hashnode.dev/master-the-shell-a-practical-introduction-to-shell-scripting-basics

Master the Shell: A Practical Introduction to Shell Scripting Basics ‍
Introduction:
In the fast-paced world of DevOps, efficiency is key, and automation is the name of the game. One of the unsung heroes in this realm is shell scripting. Whether you're a seasoned DevOps engineer or just starting your journey, diving into the world of shell scripting can significantly boost your productivity. In this blog post, we'll explore the basics and unveil the magic of automating repetitive tasks with just a few lines of code.

Shell is a program that takes commands and passes them to operating system (kernel) to carry out. Shell accept human readable commands from user and convert them into something which kernel can understand.

Shell Scripting:

Shell scripting is set of shell commands given to kernel to perform specific tasks.

Common Shell Scripting Uses:

Automating repetitive tasks like file copying or backups.

Managing and manipulating files and directories.

Triggering system events at specific times or in response to certain conditions.

Interacting with programs and applications from the command line.

Building custom tools and utilities.

Simple example of shell script:
Print something :


#!/bin/bash
#This is my first script
echo "Hello everyone! Myself Prathamesh."
echo "I will complete #90DaysOofDevOps challenge"
![image](https://github.com/Prathameshchatte/90DaysOfDevOps/assets/149644174/9284b3a1-c58c-43a0-adbb-06e514ef2a62)


Oops ! Permission Denied 😕......
Don't Worry, We need to set the script file’s permissions to allow execution.
![image](https://github.com/Prathameshchatte/90DaysOfDevOps/assets/149644174/283e206a-900b-4a2a-baa0-6a74373430d4)



Scripts can have two main permission settings:

755 allows everyone to execute the script.

700 allows only the owner to execute the script.

Remember, scripts need to be readable to be executed.

What is Shebang Line?

The line #!/bin/bash at the beginning of a shell script is called as the shebang line. It tells the operating system which interpreter to use to run the script.

In this case, #!/bin/bash tells the operating system to use the Bash shell to run the script.

BASH (Bourne Again SHell) : Most widely used and used as a default login shell in Linux and mac OS systems.

What is #!/bin/sh?

The line #!/bin/sh is also a shebang line, but it tells the operating system to use the default shell to run the script.
On most Linux systems, the default shell is Bash, so #!/bin/bash and #!/bin/sh will often have the same effect.

Then what's the difference🤔between #!/bin/bash and #!/bin/sh

The main difference between #!/bin/bash and #!/bin/sh is that #!/bin/bash explicitly specifies that the Bash shell should be used, while #!/bin/sh allows the operating system to use default shell.

Task 1: Write a Shell Script to take user input, input arguments and print the arguments.

![image](https://github.com/Prathameshchatte/90DaysOfDevOps/assets/149644174/97a4f23c-b35e-43ea-8851-5f7afedc5a4a)




Task 2 : Write an Example of If else in Shell Scripting by comparing 2 numbers
![image](https://github.com/Prathameshchatte/90DaysOfDevOps/assets/149644174/ee9d0057-7291-4691-b80a-8d35c636a062)

![image](https://github.com/Prathameshchatte/90DaysOfDevOps/assets/149644174/1289249d-7a1c-4fc0-befb-951f4d7f6ae7)

Conclusion :

Embracing shell scripting opens doors to a world of efficiency and productivity in the realm of DevOps. From automating mundane tasks to crafting custom solutions, the possibilities are endless. Remember, even as a newcomer, diving into shell scripting can yield immediate benefits. So, equip yourself with the basics, harness the magic of automation.
I hope this blog sparked your curiosity about shell scripting! Now it's your turn to grab the reins and write your own automation magic.
