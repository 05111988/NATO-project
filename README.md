# NATO-project
This project is a Python program that converts any word entered by the user into its equivalent NATO phonetic alphabet codes. It uses a CSV file as a data source and leverages pandas for reading and processing the data.
📌 Project Overview

This project takes a word input from the user and outputs a list of corresponding NATO phonetic code words. It reads a CSV file containing the phonetic alphabet data and uses dictionary comprehension for fast mapping.
✅ Features

Converts letters into NATO phonetic words.

Handles invalid inputs gracefully.

Uses pandas for efficient CSV data handling.

Simple and interactive command-line interface.
🛠️ Tech Stack

Language: Python 3

Libraries: pandas

Environment: Jupyter Notebook
📂 Project Structure
NATO-Phonetic-Alphabet/
│
├── NATO ALPHABET.ipynb     # Main Jupyter Notebook
├── nato_phonetic_alphabet.csv  # CSV file with phonetic codes
└── README.md               # Project Documentation
🚀 How to Run
1. Clone the Repository
   git clone https://github.com/your-username/NATO-Phonetic-Alphabet.git
cd NATO-Phonetic-Alphabet
2. Install Dependencies

Make sure you have pandas installed:
pip install pandas

▶️ Usage Example
Enter a word: HELLO
Output: ['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
If you enter invalid characters (like numbers or symbols), it will prompt:
Sorry, only letters in the alphabet please.
🧠 Key Concepts Covered

Reading CSV with pandas.

Dictionary comprehension with iterrows().

Exception handling in Python (try/except).
