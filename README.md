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
<img width="885" height="67" alt="image" src="https://github.com/user-attachments/assets/82f304e1-2f2b-4b52-9917-c298669ad643" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="884" height="95" alt="image" src="https://github.com/user-attachments/assets/b58a5504-850d-4f0b-9df2-cb1904aa8a14" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="911" height="417" alt="image" src="https://github.com/user-attachments/assets/ef0c69c6-c8a0-4022-96ef-62e02fd3f5d9" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="329" height="128" alt="image" src="https://github.com/user-attachments/assets/110dfa74-db68-465d-b746-a207980f832a" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="933" height="185" alt="image" src="https://github.com/user-attachments/assets/d7d3510d-1bf2-470d-9d4f-f522c13ba1ae" />

<img width="439" height="160" alt="image" src="https://github.com/user-attachments/assets/2260e792-69fb-4a3e-b565-3155e005ee4e" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="896" height="270" alt="image" src="https://github.com/user-attachments/assets/35c4b945-bc4a-4c18-816f-dc40d4c5a71e" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="905" height="401" alt="image" src="https://github.com/user-attachments/assets/8e7c875c-faa0-432f-9940-34b8fe22236c" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="941" height="434" alt="image" src="https://github.com/user-attachments/assets/5796250a-ec2c-4459-a124-0268e2883dea" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="936" height="281" alt="image" src="https://github.com/user-attachments/assets/1bc8e034-f4fe-4d9e-bb27-cacb8ea665f1" />
## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="897" height="87" alt="image" src="https://github.com/user-attachments/assets/e5d9c03e-fe7e-453d-80f1-76f3c7cbb20f" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="822" height="234" alt="image" src="https://github.com/user-attachments/assets/d15fa853-e996-41d3-810f-346777bf543b" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="782" height="176" alt="image" src="https://github.com/user-attachments/assets/a1dc0f0d-95e7-460a-8f3c-88a58dca7bf3" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="945" height="360" alt="image" src="https://github.com/user-attachments/assets/c3883700-b00e-4ddf-adc2-2794fa9c5b79" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="915" height="396" alt="image" src="https://github.com/user-attachments/assets/07f31ffb-0938-491f-998f-8f33f5eb1420" />


# RESULT:
The commands/batch files are executed successfully.

