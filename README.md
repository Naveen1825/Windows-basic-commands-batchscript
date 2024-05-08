# Windows-basic-commands-batchscript

Ex08-Windows-basic-commands-batchscript

## AIM :

To execute Windows basic commands and batch scripting

## DESIGN STEPS :

### Step 1 :

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2 :

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3 :

Execute the necessary commands/batch file for the desired output. 

## WINDOWS COMMANDS :
## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT :

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/1f556197-dfd8-4253-bc08-860d9f64a969)
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/f4f16ae3-20d2-4b43-aaf9-f76019ab6c47)

![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/46f728a2-b623-4e30-bc44-1fc8ecf33a35)


## COMMAND AND OUTPUT :

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/f9e91921-5469-4d06-97db-2f777de17704)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/8af23df1-752a-417e-b5ef-a083183e9df9)

## COMMAND AND OUTPUT :

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/f871c5a2-93ff-4408-b133-2c34c537d2d1)


## COMMAND AND OUTPUT :

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/d8ba42f1-14b0-4276-8157-a2f8614d70ac)

## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT :
![image](https://github.com/Naveen1825/Windows-basic-commands-batchscript/assets/138969868/35b1ecdd-f6dc-4f0c-9026-878981fc3866)

## RESULT :
The commands/batch files are executed successfully.

