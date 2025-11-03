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

## COMMAND AND OUTPUT

<img width="773" height="107" alt="image" src="https://github.com/user-attachments/assets/80c21ad7-fb5f-492c-b637-1a524ca3215d" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="542" height="108" alt="image" src="https://github.com/user-attachments/assets/8b62ef89-0bce-4ba7-9e5f-7e9111a5d99c" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="891" height="470" alt="image" src="https://github.com/user-attachments/assets/6c9ea8be-16a3-4823-9ada-e2a5e3456f7c" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="623" height="192" alt="image" src="https://github.com/user-attachments/assets/d96bb7fb-3d23-42c2-ab99-8c57363e00b0" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="617" height="122" alt="image" src="https://github.com/user-attachments/assets/a30d3f1f-7c9e-4065-9c3a-6fd3fd265c10" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="582" height="252" alt="image" src="https://github.com/user-attachments/assets/7b25b6a9-20e2-49c7-a5ad-b5a94f66cc13" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="582" height="252" alt="image" src="https://github.com/user-attachments/assets/6c9458e5-b9b9-45af-80ec-06eaa1ae91cd" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="795" height="687" alt="image" src="https://github.com/user-attachments/assets/1bf641f3-7e9d-4a5d-8d04-97940467e931" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="586" height="245" alt="image" src="https://github.com/user-attachments/assets/59ad224d-1e1a-4699-977a-d2ffe7291a60" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="470" height="97" alt="image" src="https://github.com/user-attachments/assets/0c6a858b-7ba4-4ce0-8455-db4db18bf9a3" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="645" height="267" alt="image" src="https://github.com/user-attachments/assets/b22e86d3-f423-4c68-8c82-783bd0a3414d" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="632" height="262" alt="image" src="https://github.com/user-attachments/assets/f441571e-d6fe-461a-bb27-bf85795f8b6b" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="622" height="195" alt="image" src="https://github.com/user-attachments/assets/bc513925-1c2d-4535-9411-7daf2f500655" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="807" height="542" alt="image" src="https://github.com/user-attachments/assets/191ab3ee-0387-4983-bb73-e6586c19c32f" />



# RESULT:
The commands/batch files are executed successfully.

