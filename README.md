
--- Created by Ridham Kumar ---

# SecurePass Generator

SecurePass Generator is a Java console application designed to generate random, secure passwords and assess their strength. Whether you need a strong password or want to check the robustness of an existing one, SecurePass provides an easy and effective solution.

## Introduction

This project was conceived during the Winter Break of my third year while taking the Object-Oriented Effective Java Programming course. Eager to apply my knowledge, I sought a practical project to develop. The idea struck one evening while discussing password security with my father, prompting me to create a random password generator. Within a week, the initial version was complete.

While developing SecurePass Generator, I realized the importance of evaluating password strength. Therefore, I incorporated a feature to assess the overall security of a password based on industry-standard criteria. Although the console-based interface was functional, I plan to develop a more user-friendly GUI, which is currently available in the Password-Services repository.

## Key Features

### 1. Password Generation

- Answer simple "Yes" or "No" questions about including uppercase letters, lowercase letters, numbers, and symbols.
- Specify the desired length of the password.
- A custom password alphabet is generated based on your preferences.
- SecurePass randomly selects characters from this alphabet to create a password that meets your specifications.
- The generated password is displayed on the console.

### 2. Password Strength Check

The strength check is based on the following criteria:
- The password uses uppercase letters.
- The password uses lowercase letters.
- The password uses numbers.
- The password uses symbols.
- The length of the password is 8 or more (8 is often the minimum required length for a decent password).
- The length of the password is 16 or more (16 is considered to be the minimum length for a good password).

These criteria are used to calculate a score for the password, which determines the message displayed to the user indicating the strength of the password (weak/medium/good/great).

### 3. Useful Information

- Offers essential tips on password security, such as avoiding repetition, keyboard patterns, dictionary words, and common sequences.
- Helps users understand best practices for creating secure passwords and safeguarding digital accounts.

## Getting Started

To run SecurePass Generator on your machine:

1. **Ensure Java is Installed:**
   - Verify that Java is installed on your system. You can check by running `java -version` and `javac -version` in your terminal or command prompt. If Java is not installed, download and install the Java Development Kit (JDK) from the [official Java website](https://www.oracle.com/java/technologies/javase-downloads.html).

2. **Clone or Download the Repository:**
   - Clone the repository using:
     git clone <repository-url>
     
   - Or download the ZIP file and extract it.

3. **Navigate to the Source Directory:**
   - Open a terminal or command prompt and change to the directory containing the source files:

     cd path\to\Password-Generator-master\Password Generator\src

4. **Compile the Source Files:**
   - Compile the Java source files using:

     javac *.java


5. **Run the Application:**
   - Execute the main class:
     
     java Main


6. **Follow the Prompts:**
   - The program will display a menu. 1. Enter your choice to generate a password,2.  check its strength 3. view security tips.


--- Created by Ridham Kumar ---

