# EXP 7 :USING JOHN THE RIPPER FOR PASSWORD CRACKING

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212222040121
Name: Praveen V
```

## DESIGN STEPS:
### Step 1:
Install John the Ripper in Kali linux

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).

### Step 3:
Use John the Ripper to crack the hashes

## PROCEDURE:
### Step 1: Create a Text File

  •	Right-click on the Desktop and choose Create Document → Empty Document.
  
  •	Name the file: praveen.txt.

  ![image](https://github.com/user-attachments/assets/936d80e5-b2b5-4e26-a0e2-11e1f359cf0d)

  •	Open it and type:

  ![image](https://github.com/user-attachments/assets/c471f666-1632-4dee-81d0-b43d97d8e6f7)

  •	Save and close the file.

### Step 2: Create a Password-Protected ZIP File

  •	Right-click on praveen.txt → Create Archive.
  
  ![image](https://github.com/user-attachments/assets/401099f6-f9b0-47af-8065-8daf3bde16d4)

  •	Select .zip format.
  
  •	Click Other Options, set a password (e.g., 1234), then click Create.

  ![image](https://github.com/user-attachments/assets/c2621395-c93e-4083-9bdd-333a3f0a95c8)

  •	A file named praveen.txt.zip will appear.

### Step 3: Open John the Ripper Terminal in Kali Linux

  •	Click on the Kali menu or press the Super (Windows) key.
  
  •	Search for “john” and click it — this opens the terminal with John the Ripper installed.

  ![image](https://github.com/user-attachments/assets/da33af62-448c-4d21-a76e-832fc6f11ede)

  •	Or simply open a Terminal from the dock or desktop.

### Step 4: Navigate to the File Location

  •	In the terminal, switch to the Desktop where the ZIP file is located:
  
  ![image](https://github.com/user-attachments/assets/8f16dd47-a74a-4ace-93b4-9646a492d6aa)

### Step 5: Confirm the ZIP File is Present

  •	Run: “ls” command
  
  ![image](https://github.com/user-attachments/assets/993d8812-b369-48b2-b5b4-87ab6244c288)

  •	You should see praveen.txt.zip listed.

### Step 6: Generate Hash Using zip2john

  •	Execute:
  ![image](https://github.com/user-attachments/assets/586d8286-0586-4d08-b4b8-a99675b5e94a)

### Step 7: Verify the Hash File (Optional)
  •	Open hash.txt to ensure it contains the hash line.
  ![image](https://github.com/user-attachments/assets/e0af1389-4671-471e-b159-84a1c8e8ed0e)

### Step 8: Start Cracking the Password
  •	Run:
  ![image](https://github.com/user-attachments/assets/587ad087-542e-4087-a14c-d7c71cca9cc0)

## OUTPUT:View the Cracked Password
  • After cracking is complete, reveal the password using:
  ![image](https://github.com/user-attachments/assets/4816226e-22cf-47b7-89bc-92f68082284f)

  •	The terminal will display the filename and its cracked password.


## RESULT:
The password hashes were successfully cracked using John the Ripper.

