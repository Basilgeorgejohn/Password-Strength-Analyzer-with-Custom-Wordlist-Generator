# Password-Strength-Analyzer-with-Custom-Wordlist-Generator

# Password Strength Analyzer with Custom Wordlist Generator

A comprehensive cybersecurity tool built with Python that analyzes password strength and generates custom wordlists for penetration testing and security assessments.

<img width="1920" height="945" alt="Screenshot_2025-09-13_12_01_11" src="https://github.com/user-attachments/assets/99fa84e7-7a87-463a-ab49-0039cf648142" />




## Features

### Password Strength Analysis
- **Entropy-based security evaluation** - Calculates password strength using mathematical entropy algorithms
- **Detailed feedback system** - Provides specific suggestions for improving password security
- **Visual strength indicators** - Clear rating system with color-coded results


## Password Strength Analysis: Types and Categories
Password Strength Levels
1. Very Weak Password (0/4)

    Characteristics:

        Extremely short (<6 characters)

        Common words or patterns ("password", "123456")

        No complexity (all lowercase letters or all numbers)

    Cracking Time: Seconds to minutes

    Examples: "password", "12345", "qwerty"

   <img width="1920" height="945" alt="Screenshot_2025-09-13_12_01_27" src="https://github.com/user-attachments/assets/f6a5b851-f1a4-4f0b-b37c-82de4fe379cd" />

2. Moderate Password (2/4)

    Characteristics:

        Medium length (8-12 characters)

        Mix of character types (upper, lower, numbers)

        Not based on common words or patterns

    Cracking Time: Days to weeks

    Examples: "Blue42Sky!", "Runner@2023", "Tree$House5"

   <img width="1920" height="945" alt="Screenshot_2025-09-13_12_01_39" src="https://github.com/user-attachments/assets/a7223846-cab0-4cdb-9e8b-0abdcbf406b6" />

3. Strong Password (3/4)

    Characteristics:

        Good length (12-16 characters)

        Multiple character types (upper, lower, numbers, symbols)

        No dictionary words or predictable patterns

    Cracking Time: Months to years

    Examples: "J8$kL2@mN9#pQ1!", "X7*gH4%wR2&tY6^"

   <img width="1920" height="945" alt="Screenshot_2025-09-13_12_02_12" src="https://github.com/user-attachments/assets/0b0142d7-ecd4-49e6-8a98-7194ba140ea5" />

4.Very Strong Password (4/4)

    Characteristics:

        Long length (16+ characters)

        Full character set diversity

        Random appearance with no predictable patterns

        Passphrase-based with special characters

    Cracking Time: Decades to centuries

    Examples: "CorrectHorseBatteryStaple$42!", "V3ry$L0ng&P@ssphraseW1thNumb3rs!"

   <img width="1920" height="945" alt="Screenshot_2025-09-13_12_02_32" src="https://github.com/user-attachments/assets/564d8b2a-0762-493f-abe3-a246e5278705" />


### Custom Wordlist Generation

<img width="1920" height="945" alt="Screenshot_2025-09-13_12_03_46" src="https://github.com/user-attachments/assets/9063c233-69af-4a51-af33-eff95aa49243" />


This password generator is a secure tool designed to create strong, unique, and 
- **Personalized dictionaries** - Creates targeted wordlists from personal information
- **Leetspeak patterns** - Implements character substitutions (a→@, e→3, etc.)
- **Year variations** - Generates years from 1970 to current year +1
- **Common password patterns** - Includes prefixes, suffixes, and capitalization variations

- <img width="1920" height="945" alt="Screenshot_2025-09-13_12_03_53" src="https://github.com/user-attachments/assets/ea991905-a731-4fc7-871b-3ce16e4e9831" />



*Wordlist generation interface with input fields for personal information*

### Dual Interface
- **Graphical User Interface (GUI)** - User-friendly tabbed interface with Kali Linux theme
- **Command-Line Interface (CLI)** - Scriptable interface for automation and integration

