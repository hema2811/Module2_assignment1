# Maintaining Efficient process Utilization on windows 
1.view the current tasks using the task manager 

2.Find the pid of the process you want to kill. GO to task manager and click details to find the pid number.

3.Then open windows powershell and type the comamand taskkill/pid (pid number).The corresponding processes running will be terminated.

4. To kill multiple tasks, type the command taskkill/pid (pid number )/ pid .
