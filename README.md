# Password Strength Tracker

## 1. Introduction

The Password Strength Tracker is a Python-based project that checks how strong or weak a password is. It helps users understand whether their password is secure by checking its length and the types of characters it contains.

The main aim of this project is to encourage users to create strong passwords and improve their online security.

## 2. Objectives

* To check the strength of a password.
* To identify weak passwords that may be easy to guess.
* To encourage the use of strong and secure passwords.
* To understand the use of Python conditional statements and string functions.

## 3. Features

* **Password Length Check:** Checks whether the password contains enough characters.
* **Uppercase Check:** Checks for capital letters (A–Z).
* **Lowercase Check:** Checks for small letters (a–z).
* **Number Check:** Checks whether the password contains digits (0–9).
* **Special Character Check:** Checks for symbols such as @, #, $, and !.
* **Strength Rating:** Classifies the password as Weak, Medium, or Strong based on the checks it passes.

## 4. Technologies Used

* **Programming Language:** Python
* **Modules:** `string` 
* **Concepts:** Conditional statements, loops ,strings, and user input.

## 5. How It Works

1. The program asks the user to enter a password.
2. It checks the password's length.
3. It checks whether the password contains uppercase letters, lowercase letters, numbers, and special characters.
4. It calculates the strength based on the conditions satisfied.
5. It displays the final result as Weak, Medium, or Strong.

## 6. How to Run the Project

1. Install Python on your computer.

2. Save the Python code in a file named `password_strength_tracker.py`.

3. Open a terminal or command prompt in the folder containing the file.

4. Run the following command:

   ```bash
   python password_strength_tracker.py
   ```

5. Enter a password when prompted and view the strength rating.

## 7. Example Output

```text
Enter your password: Hello@123
Password Strength: Strong
```

## 8. Advantages

* Easy to use and understand.
* Helps users identify potentially weak passwords.
* Encourages better password-creation habits.
* Provides practical experience with Python programming.

## 9. Limitations

* It checks basic password characteristics and may not detect every weak or commonly used password.
* A strong rating does not guarantee complete security.
* It does not check whether a password has been exposed in a data breach unless that feature is specifically implemented.

## 10. Future Improvements

* Add a graphical user interface (GUI).
* Include a password generator.
* Detect common or easily guessed passwords.
* Add a visual strength indicator.
* Provide suggestions for improving weak passwords.

## 11. Conclusion

The Password Strength Tracker is a beginner-friendly Python project that demonstrates how programming can be used to improve cybersecurity awareness. It evaluates passwords using basic security rules and encourages users to create stronger passwords for their online accounts.
