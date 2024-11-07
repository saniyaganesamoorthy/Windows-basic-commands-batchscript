# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/user-attachments/assets/0d160116-9dc4-4211-97c4-7a7d0ae3b432)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/01492433-8b92-463c-b479-65ef8a350265)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/e27d6168-d30f-4dca-8dad-8212f95e741e)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/b11b7482-f2b6-488e-9dde-d4b8030297a1)


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/a3f890b4-f64a-4886-b94b-245e87d096fd)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
open a notepad file named BackupScript.bat and enter the following:
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![image](https://github.com/user-attachments/assets/eca57f4b-a21c-4cf4-b7ec-5108cd2146dd)

# RESULT:
The commands/batch files are executed successfully.

