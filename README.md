# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 



# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"


<img width="413" height="128" alt="a1" src="https://github.com/user-attachments/assets/b24f09e3-db5a-4f58-87a2-d3492d0f3def" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"


<img width="344" height="35" alt="a2" src="https://github.com/user-attachments/assets/52329cdd-951e-4461-b2fd-b371aec1170b" />


## COMMAND AND OUTPUT

Create the file Rose.txt


<img width="454" height="233" alt="a3" src="https://github.com/user-attachments/assets/38cd6c1c-19c7-4648-a698-dd199b1bab22" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection


<img width="466" height="76" alt="a4" src="https://github.com/user-attachments/assets/64fa678e-b2b1-4859-8740-86d56d343848" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


<img width="428" height="92" alt="a5" src="https://github.com/user-attachments/assets/155799c0-5dc5-4fa5-87fe-f5f92672055e" />

## COMMAND AND OUTPUT

Remove the file hello1.txt


<img width="356" height="26" alt="image" src="https://github.com/user-attachments/assets/11aed524-c313-4446-a5a4-5086e164c293" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="319" height="95" alt="image" src="https://github.com/user-attachments/assets/f1497bbc-6b2a-4b32-9c2d-b34ced5c6c22" />


## COMMAND AND OUTPUT

List out all the associated file extensions 


<img width="424" height="341" alt="a7" src="https://github.com/user-attachments/assets/04465084-46b8-4503-8767-e7c8b38a3935" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt


<img width="403" height="107" alt="a8" src="https://github.com/user-attachments/assets/48e6116a-6485-4308-855e-203dd4c69c17" />


## COMMAND AND OUTPUT

<img width="334" height="181" alt="a9" src="https://github.com/user-attachments/assets/03ec53a2-5816-44d8-ae10-823dd1be1629" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



## OUTPUT


<img width="311" height="46" alt="a10" src="https://github.com/user-attachments/assets/343efafa-4c02-4754-95c1-9d5a4a55e7be" />
`

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="313" height="140" alt="a11" src="https://github.com/user-attachments/assets/5faf3a27-dae3-48c0-9f44-82737dd12b7b" />
`



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="322" height="113" alt="a12" src="https://github.com/user-attachments/assets/2ad547f8-3387-452a-81fd-610afc52006f" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="409" height="137" alt="notepad 4" src="https://github.com/user-attachments/assets/45ba13fd-eff9-474c-a5ae-824d3ed8c100" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="541" height="295" alt="notepad5" src="https://github.com/user-attachments/assets/bf8ce8d4-8188-4d35-a801-8cc53e45f13a" />


# RESULT:
The commands/batch files are executed successfully.

