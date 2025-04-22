# EXP 7 :USING JOHN THE RIPPER FOR PASSWORD CRACKING

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## EQUIPMENTS REQUIRED:
●	Hardware: PCs

```
Register Number: 212222040020
Name: Ashwinkumar S
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

  ![Screenshot 2025-04-22 202441](https://github.com/user-attachments/assets/53b5a5fb-7bc1-4acc-b1fd-2fedf6d20bd1)


  •	Open it and type:

 ![Screenshot 2025-04-22 202727](https://github.com/user-attachments/assets/8d212bcc-21c0-4795-980e-d0958c2fc612)

  •	Save and close the file.

### Step 2: Create a Password-Protected ZIP File

  •	Right-click on praveen.txt → Create Archive.
  ![Screenshot 2025-04-22 202820](https://github.com/user-attachments/assets/96393f0f-027a-4e3f-b102-825679551799)


  •	Select .zip format.
  
  •	Click Other Options, set a password (e.g., 1234), then click Create.

![Screenshot 2025-04-22 202937](https://github.com/user-attachments/assets/0da2197b-81e6-4419-aa41-8c1757ed7f91)


  •	A file named praveen.txt.zip will appear.

### Step 3: Open John the Ripper Terminal in Kali Linux

  •	Click on the Kali menu or press the Super (Windows) key.
  
  •	Search for “john” and click it — this opens the terminal with John the Ripper installed.

  ![image](https://github.com/user-attachments/assets/da33af62-448c-4d21-a76e-832fc6f11ede)

  •	Or simply open a Terminal from the dock or desktop.

### Step 4: Navigate to the File Location

  •	In the terminal, switch to the Desktop where the ZIP file is located:
  
 ![Screenshot 2025-04-22 203818](https://github.com/user-attachments/assets/a497e10e-750c-4ee5-8b95-a105725cb1ca)


### Step 5: Confirm the ZIP File is Present

  •	Run: “ls” command
  ![Screenshot 2025-04-22 203546](https://github.com/user-attachments/assets/4845b15a-5dab-45e1-ad11-81823cd5ea09)


  •	You should see praveen.txt.zip listed.

### Step 6: Generate Hash Using zip2john

  •	Execute:
 ![Screenshot 2025-04-22 203600](https://github.com/user-attachments/assets/3fe67822-f305-4fdc-a24d-02a4dadc536f)


### Step 7: Verify the Hash File (Optional)
  •	Open hash.txt to ensure it contains the hash line.
 ![Screenshot 2025-04-22 203453](https://github.com/user-attachments/assets/4086cd41-c1a0-48e1-b574-197449cddbbc)

### Step 8: Start Cracking the Password
  •	Run:
![Screenshot 2025-04-22 203948](https://github.com/user-attachments/assets/7e29d0ed-024b-4132-b8dd-a44f28f3c4d2)


## OUTPUT:View the Cracked Password
  • After cracking is complete, reveal the password using:
![Screenshot 2025-04-22 204018](https://github.com/user-attachments/assets/0ee3af93-7536-46a9-aeb2-7ddeac9411b5)


  •	The terminal will display the filename and its cracked password.


## RESULT:
The password hashes were successfully cracked using John the Ripper.

