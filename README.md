 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
    Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

1.Displaying the current directory, files, and system date. 2.Reading and displaying file contents. 3.Performing basic arithmetic operations.

## ALGORITHM
 ### Steps 1:
 open the terminal in Kali Linux.
 ### Steps 2:
 Use basic Linux commands to navigate and mangae files.
 ### Steps 3:
 Create a Bash script using Mousepad.
 ### Steps 4:
 Write a script that performs arithmetic operations and reads a file.
 ### Steps 5:
 Make the script executable.
 ### Steps 6:
 Run the script and observe the output.
## COMMANDS
## Execute Basic Linux Commands in the Terminal
## Check the Current Working Directory
```
pwd
```
## Create a New Directory
```
mkdir my_experiment
```
## Navigate into the Directory
```
cd my_experiment
```
## List the Files in the Directory
```
ls
```
## Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```
## Read the File Contents
```
cat myfile.txt
```
## Get the Current Date and Time
```
date
```
## Writing a Bash Script in Mousepad
## Open Mousepad
```
mousepad myscript.sh &
```
## Write the Bash Script
```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"
```
## Make the Script Executable
```
chmod +x myscript.sh
```
## Run the Script
```
./myscript.sh
```
## OUTPUT

### REG NUMBER:212223220084
### NAME:RAMKUMAR G
# Configuration of Kali Linux on Oracle Virtual Box :
![419319385-83f47f18-6b45-4f19-8068-7bb8b1baf013](https://github.com/user-attachments/assets/62dc95d9-448f-482e-a1c9-290de58ace39)

## Output:
![419317380-334ef340-3385-4a61-b397-9293233d6009](https://github.com/user-attachments/assets/7f5eb7f3-0c2d-4a39-979c-5188a95e66ec)

![419318252-367e463b-4a99-4823-9564-a61d6a6f2815](https://github.com/user-attachments/assets/93f0d528-e05e-4cb5-8850-7d142ec7b220)



## RESULT
 
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
  


