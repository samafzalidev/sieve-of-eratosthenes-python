# 🧮 Sieve of Eratosthenes Python

### A simple Python implementation of the classic Sieve of Eratosthenes algorithm for finding prime numbers

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Algorithm](https://img.shields.io/badge/Algorithm-Sieve%20of%20Eratosthenes-7B2CBF?style=flat)]()
[![Math](https://img.shields.io/badge/Math-Number%20Theory-0EA480?style=flat)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat)](LICENSE)
[![Website](https://img.shields.io/badge/Website-samafzali.ir-0EA480?style=flat&logo=google-chrome&logoColor=white)](https://samafzali.ir)

**Find prime numbers up to a given limit using one of the most famous and efficient classical algorithms in mathematics.**

🇮🇷 [مطالعه به فارسی](README.fa.md) · 🐛 [Report a Bug](https://github.com/samafzalidev/sieve-of-eratosthenes-python/issues) · ✨ [Request a Feature](https://github.com/samafzalidev/sieve-of-eratosthenes-python/issues)

---

## 📖 About The Project

**Sieve of Eratosthenes Python** is a small, clean, and beginner-friendly Python project that implements the well-known **Sieve of Eratosthenes** algorithm.

This algorithm is used to find all prime numbers up to a selected limit. It is simple to understand, efficient for many practical cases, and a great starting point for learning algorithms, loops, arrays/lists, and number theory concepts.

> 💡 This repository is focused on clarity and learning. The code is intentionally simple and easy to read, making it suitable for beginners and educational purposes.

---

## ✨ Key Features

- 🔢 **Prime Number Generation** — Finds prime numbers up to a given limit
- 🧠 **Classic Algorithm** — Uses the Sieve of Eratosthenes method
- 🐍 **Pure Python** — No external libraries required
- ⚡ **Efficient Approach** — Avoids checking every number one by one
- 📚 **Beginner Friendly** — Easy to read, understand, and modify
- 🧮 **Great for Math Practice** — Useful for learning number theory basics

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🐍 **Python 3.x** | Core programming language |
| 🧮 **Sieve of Eratosthenes** | Prime number generation algorithm |
| 📚 **Number Theory** | Mathematical foundation |

---

## 🧠 How The Algorithm Works

The Sieve of Eratosthenes works by marking non-prime numbers instead of testing every number separately.

It starts by assuming that all numbers are prime. Then, beginning from `2`, it marks all multiples of each prime number as non-prime. After this process finishes, the remaining marked numbers are prime numbers.

### Algorithm Steps

1. Create a boolean list from `0` to `limit`.
2. Assume all numbers are prime at first.
3. Start from the first prime number: `2`.
4. Mark all multiples of the current prime as non-prime.
5. Move to the next number.
6. Repeat while `p * p <= limit`.
7. Return all numbers that are still marked as prime.

---

## 🚀 Getting Started

### 📋 Prerequisites

Make sure **Python 3.x** is installed on your system:

```bash
python --version
```

or:

```bash
python3 --version
```

---

## 📥 Installation

1. **Clone the repository**

```bash
git clone https://github.com/samafzalidev/sieve-of-eratosthenes-python.git
```

2. **Go to the project directory**

```bash
cd sieve-of-eratosthenes-python
```

3. **Run the script**

```bash
python sieve_of_eratosthenes.py
```

On some systems, you may need to use:

```bash
python3 sieve_of_eratosthenes.py
```
---

## 🎮 Usage

You can change the value of `limit` to generate prime numbers up to a different range:

```python
limit = 1000
```

For example:

```python
limit = 100
```

Then run the script again to see the updated list of prime numbers.

---

## 📤 Example Output

For:

```python
limit = 1000
```

The program prints prime numbers less than `1000`:

```txt
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, ...]
```

---

## ⏱️ Complexity

| Type | Complexity |
|---|---|
| **Time Complexity** | `O(n log log n)` |
| **Space Complexity** | `O(n)` |

---

## 📁 Project Structure

```txt
sieve-of-eratosthenes-python/
├── 📄 sieve_of_eratosthenes.py   # Main Python script
├── 📄 README.md                  # English documentation
├── 📄 README.fa.md               # Persian documentation
└── 📄 LICENSE                    # MIT License
```

---

## 🏷️ Suggested GitHub Topics

```txt
python
algorithm
prime-numbers
sieve-of-eratosthenes
mathematics
number-theory
beginner-friendly
```

---

## 🗺️ Roadmap

Possible improvements for future versions:

- [ ] Add command-line input for the limit
- [ ] Add input validation
- [ ] Include prime count summary
- [ ] Add unit tests
- [ ] Add an optimized version using slicing
- [ ] Add comparison with a basic prime-checking method

Have an idea? [Open an issue](https://github.com/samafzalidev/sieve-of-eratosthenes-python/issues) to suggest it!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 🎉

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

> ⭐ If you like this project, please consider giving it a **star** — it helps a lot!

---

## 📜 License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for more information.

---

## 👨‍💻 Author

### **Sam Afzali** — Software, Web & AI Developer

🌐 **Website:** [samafzali.ir](https://samafzali.ir)  
🐙 **GitHub:** [@samafzalidev](https://github.com/samafzalidev)  
📨 **Telegram:** [@samafzalidev](https://t.me/samafzalidev)

_Designed & developed with ❤️ in Iran_

---

**If this project was helpful, don't forget to leave a ⭐ on GitHub!**

Made with ❤️ by [Sam Afzali](https://github.com/samafzalidev)
