# Port

At any instance of time, a computer could be executing hundredes of programs (a program in execution is called a process). To find the number of processes currently being executed on your machine (computer), try the following steps:
  1. Open Command Prompt or PowerShell: Press `Win + R`, type cmd or powershell, and press `Enter`.
  2. Run the following command: `tasklist | find /c /v ""`

The number of processes running depends on your system configurations and number of applications you have open. Let's take an example of a web browser, an application via which you are most probably reading this tutorial. 
Currently, you might have multiple tabs open. Maybe at one tab you are doing some Google search. Maybe on another a there's YouTube. 
> [!IMPORTANT]
> Now the question is.. how can we ensure that data sent over a network reaches the correct application on a computer?

If you were supposed to design a solution, how would you start? (Brainstorm!)
Think about:
  1. How to identify different applications on a computer.
  2. How to ensure that the data will not be mixed up.
  3. How to make your solution easy to use and scalable.
 
 Real-world addressing is a similar problem that exists in a different form: You live in a house along with your family. If I want to send you a post from a different country, how'd I do that?
 First of all I should be knowing you such that I can identify you. I can do this by your name. But, there can be thousands of people with the same name in your country. Therefore, I need your home address too. 
 In essence, by using your home address and your name I can send you a post. 

 We can do the same for the processes as well. Instead of a name, they are identified by a number (port number) and instead of a home address they have IP address. We can send a message to a process on a particular machine with the 
 help of an IP address and a port number. 
 
