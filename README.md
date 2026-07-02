# Word Search System 

# Overview

The **Document Word Search System** is a beginner-friendly Python application that enables users to search for specific words within **Text (.txt)** and **PDF (.pdf)** documents. The application provides a simple graphical interface for selecting files and performs a case-insensitive search to locate the requested word.

For text files, the program displays the **line number** along with the matching line. For PDF files, it identifies the **page number** where the word appears and displays the corresponding text.

This project demonstrates fundamental Python programming concepts such as file handling, GUI development, string manipulation, conditional statements, loops, and PDF document processing.

# Features

*  Browse and select files directly from your computer using a file picker.
*  Supports both **TXT** and **PDF** document formats.
*  Performs case-insensitive word searching.
*  Displays:

 * Line numbers for TXT files.
* Page numbers for PDF files.
*  Shows the line or text containing the searched word.
*  Displays a clear message when the searched word is not found.
*  Simple command-line interaction combined with a graphical file selection window.
*  Fast and lightweight with minimal dependencies.

---

# Technologies Used

| Technology | Purpose                                    |
| ---------- | ------------------------------------------ |
| Python 3   | Core programming language                  |
| Tkinter    | Graphical file selection dialog            |
| PyPDF2     | Reading and extracting text from PDF files |
| OS Module  | File type detection and path handling      |

---

# Installation

# 1. Clone the repository

```bash
git clone https://github.com/your-username/document-word-search.git
```

# 2. Navigate to the project directory

```bash
cd document-word-search
```

### 3. Install the required dependency

```bash
pip install PyPDF2
```

or

```bash
python -m pip install PyPDF2
```

# Running the Application

Execute the Python file:

```bash
python main.py
```

A file selection window will appear.

1. Choose a **TXT** or **PDF** document.
2. Enter the word you wish to search.
3. View the search results displayed in the terminal.

# Supported File Types

| File Type | Supported       |
| --------- | --------------- |
| .txt      |   Yes           |
| .pdf      |   Yes           |
| .docx     |   Not Supported |
| .xlsx     |   Not Supported |

# Example

# Sample Text File

```
Python is easy to learn.
Java is widely used.
Python is powerful.
```

# Search Input

```
python
```

# Output

```
Found on Line 1
Python is easy to learn.

Found on Line 3
Python is powerful.
```

# Sample PDF

If the searched word exists on Page 4:

```
Found on Page 4

Python supports object-oriented programming.
```


# Project Structure

```
Document-Word-Search/
│
├── main.py
├── README.md
└── requirements.txt
```


# Concepts Demonstrated

This project helped in understanding and implementing:

* Python File Handling
* Reading Text Files
* Reading PDF Documents
* GUI File Selection using Tkinter
* String Searching
* Conditional Statements
* Loops
* Functions
* Python Modules and Packages
* User Input Handling
* Basic Error Handling


# Future Improvements

The following enhancements can be implemented in future versions:

* Search multiple words simultaneously.
* Display the total number of occurrences of each word.
* Highlight matching words inside documents.
* Export search results to a text or CSV file.
* Add support for Microsoft Word (.docx) documents.
* Search through multiple files within a selected folder.
* Develop a complete graphical user interface using Tkinter or CustomTkinter.
* Add drag-and-drop functionality for file selection.
* Implement regular expression (Regex) searching.
* Add filters for exact word matching and partial matching.

---

# Learning Objectives

This project was developed as a learning exercise to strengthen knowledge of:

* Python programming fundamentals
* Document processing
* GUI development
* File handling techniques
* Third-party Python libraries
* Practical problem solving

---

# Contributions

Contributions, suggestions, and improvements are welcome.

If you have ideas for enhancing this project, feel free to fork the repository, create a new branch, and submit a pull request.

---

# License

This project is available under the MIT License. You are free to use, modify, and distribute it for educational and personal purposes.

# Author

**Kamesh Kedare**

Bachelor of Science (Computer Science)

Passionate about Python, Java, Data Structures & Algorithms, and Software Development.

 If you found this project useful or interesting, consider giving the repository a star!
