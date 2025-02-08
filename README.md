# Password-Generator
🔐 Random Password Generator

A simple Random Password Generator built using Python. This program generates secure and strong passwords of a user-defined length using a combination of uppercase letters, lowercase letters, digits, and special characters.


---

🏆 Internship Details

Internship Provider: CodSoft

Internship Type: Python Programming Internship

Project: Random Password Generator in Python


This project was developed as part of my internship at CodSoft, where I am learning and applying Python programming concepts by building practical applications.


---

📌 Features

✅ Generates a secure random password.

✅ Uses a combination of uppercase, lowercase, numbers, and special characters.

✅ Takes user input for the desired password length.

✅ Ensures a minimum length of 1 to avoid errors.

✅ Handles invalid user inputs gracefully.



---

🛠 How to Use

1️⃣ Run the Script

Make sure you have Python 3.x installed on your system. Run the script using:

python password_generator.py

2️⃣ Enter the Desired Password Length

When prompted, enter the length of the password you want.

Enter the desired password length: 12
Generated Password: @Xf8!aL2s#1Q

If an invalid input is given (like a negative number or a non-numeric value), the program will show an appropriate message.


---

📜 Code Explanation

The script consists of the following parts:

generate_password(length)

Uses Python’s random module to generate a secure password.

Selects random characters from uppercase letters, lowercase letters, digits, and special symbols.

Returns the generated password as a string.


User Input Handling

Takes user input for password length.

Ensures the input is a valid positive integer.

If input is invalid, it displays an appropriate message.


Main Execution

Calls the generate_password() function and prints the generated password.



---

🎯 Example Usage

✅ Valid Input

Enter the desired password length: 10
Generated Password: hT@9!xK2Y&

❌ Invalid Input (Negative Number)

Enter the desired password length: -5
Password length must be at least 1.

❌ Invalid Input (Non-Numeric)

Enter the desired password length: abc
Please enter a valid number.


---

🚀 Requirements

Python 3.x

No additional libraries are required (uses built-in modules random and string).



---

🏗 Project Structure

📂 Random Password Generator Project
│── 📄 password_generator.py   # Main Python script
│── 📄 README.md               # Documentation file


---

🔗 Future Improvements

✅ Allow users to include/exclude special characters.
✅ Provide an option for only letters, numbers, or symbols.
✅ Save generated passwords to a file for future use.
✅ Develop a GUI version using Tkinter or PyQt.


---

📜 License

This project is free to use and distribute. Feel free to modify and improve it!


---

This README.md file now includes all details about your Random Password Generator Project. Let me know if you need any modifications! 🚀
