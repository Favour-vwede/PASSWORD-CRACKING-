# PDF Password Cracking Using John the Ripper & Networkwalks Tools

## Project Overview

This project demonstrates two approaches to recovering passwords from password protected PDF files using cybersecurity tools:

# 1) John the Ripper (Johnny GUI)
# 2)Networkwalks Hash Calculator and Password Cracker

The exercise explores how password hashes are extracted from PDF files and how password cracking tools attempt to recover the original passwords.

# Disclaimer: This exercise was performed for educational purposes in an authorized cybersecurity lab environment, using files permitted for password recovery.

---

## Tools Used

| Tool | Purpose |
|---|---|
| John the Ripper | Password hash cracking |
| Johnny GUI | Graphical interface for John the Ripper |
| PDF Hash Extractor | Extracts password hashes from PDF files |
| Networkwalks Hash Calculator | Generates/calculates hashes |
| Networkwalks Password Cracker | Attempts to recover passwords from supplied hashes |
| Kali Linux | Testing environment |

---

## Method 1: Using John the Ripper (Johnny GUI)

# Step 1: Extract the PDF Hash
- Open the PDF Hash Extractor.
- Select the password protected PDF file.
- Extract the password hash from the document.

# Step 2: Save the Hash
- Copy the extracted hash.
- Open a text editor.
- Paste the hash into a new text file.
- Save the file for use with John the Ripper.

# Step 3: Load the Hash into Johnny
- Launch Johnny (the graphical interface for John the Ripper).
- Click Open Password File
- Locate and select the text file containing the extracted hash.

# Step 4: Start the Attack
- Click Start New Attack
- Allow Johnny to process the hash.
- Monitor the attack until the password is successfully recovered or the attempt ends.

# Step 5: Verify the Result
- Record the recovered password if successful.
- I tesed the result against the authorized PDF file and i was able to unlock it.

---

## Method 2: Using Networkwalks Tools

### Step 1: Generate the Hash
- I opened the Networkwalks Hash Calculator and input the locked pdf file ( https://networkwalks.com/hash-calculator/ ).

### Step 2: Copy the Hash
- I Copied the generated hash from the Hash Calculator.

### Step 3: Open the Password Cracker
- Navigate to the Networkwalks Password Cracker (https://networkwalks.com/password-cracker/).
- Paste the copied hash into the appropriate input field.

### Step 4: Start the Cracking Process
- Submit the hash.
- Allow the Networkwalks Cracker to process it.

### Step 5: Record the Result
- Document the outcome of the cracking attempt.
- Compare the results with the John the Ripper method.

---

## Comparison of Both Methods

| Feature | John the Ripper | Networkwalks |
|---|---|---|
| Hash extraction | PDF Hash Extractor | Networkwalks Hash Calculator |
| Hash input | Saved text file | Direct hash input |
| Interface | Johnny GUI | Networkwalks web tool |
| Cracking process | Start New Attack | Start cracking |
| Result | Recovered password, if successful | password cracked successfully |

---

## Skills Gained

- Understanding password hashes.
- Learning how password hash extraction works.
- Practical exposure to John the Ripper.
- Using graphical password-auditing interfaces.
- Working with Networkwalks cybersecurity tools.
- Understanding basic password security and recovery.
- Comparing different password-auditing approaches.

---

## Conclusion

This project provided practical experience with two password-auditing approaches and improved my understanding of how password hashes are extracted, submitted, and processed by password-cracking tools.

It also highlighted the importance of using strong passwords to protect sensitive documents.

**Project completed as part of my cybersecurity learning journey and internship experience.**

#Cybersecurity #JohnTheRipper #Networkwalks #PasswordSecurity #KaliLinux #EthicalHacking