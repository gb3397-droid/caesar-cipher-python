# 🔐 Caesar Cipher – Python Implementation

## 📌 Project Overview

This project is a **command-line implementation of the Caesar Cipher encryption algorithm**, developed using Python.

The program allows users to:

* Encrypt a message (encode)
* Decrypt a message (decode)
* Apply a customizable shift value
* Restart the program multiple times

The implementation handles alphabet shifting while preserving non-alphabet characters such as spaces, numbers, and symbols.

---

## 🎯 Why This Project?

I built this project to understand how classical encryption algorithms work and how text transformation can be implemented programmatically.

The Caesar Cipher is one of the earliest known cryptographic techniques and provides a strong foundation for understanding:

* Substitution ciphers
* Modular arithmetic
* String manipulation
* Algorithm design

This project strengthened my understanding of logic flow and data transformation in Python.

---

## 🧠 Core Concepts Used

* Function definition and parameter passing
* Loops (`for`, `while`)
* Conditional statements
* Modular arithmetic (`%`)
* List indexing
* String manipulation
* Program restart logic
* Basic encryption algorithms

---

## 🗂️ Project Structure

```
caesar-cipher-python/
│
├── main.py
├── art.py
└── README.md
```

### 🔹 `main.py`

Contains:

* Core cipher logic
* Encoding and decoding functionality
* Restart loop
* User interaction handling 

### 🔹 `art.py`

Contains:

* ASCII logo displayed when the program starts

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/caesar-cipher-python.git
   ```

2. Navigate to the project directory:

   ```bash
   cd caesar-cipher-python
   ```

3. Run the program:

   ```bash
   python main.py
   ```

4. Follow the prompts to encode or decode your message.

---

## 🔎 How the Algorithm Works

1. The user selects encode or decode.
2. A shift value is provided.
3. Each letter is shifted forward or backward in the alphabet.
4. Modular arithmetic ensures wrapping from `z` to `a`.
5. Non-alphabet characters remain unchanged.

Example:

* Original: `hello`
* Shift: `3`
* Encoded: `khoor`

---

## 🎓 Learning Outcomes

Through this project, I learned how to:

* Implement classical encryption algorithms
* Apply modular arithmetic in real programs
* Design reusable functions
* Build restartable command-line tools
* Handle edge cases in string processing

---

## 🚀 Future Improvements

* Add input validation for incorrect shift values
* Support uppercase letters explicitly
* Add multiple cipher techniques
* Convert to GUI version
* Build a small cryptography toolkit

---

## 👤 Author

**B. Gowtham**

First-Year B.Tech (Artificial Intelligence) Student

SRM Institute of Science and Technology, Ramapuram Campus

📍 Chennai, India

🔗 LinkedIn: https://www.linkedin.com/in/gowtham-balu-3a5763377

---

⭐ *Building algorithmic thinking through classical encryption techniques.*

---

