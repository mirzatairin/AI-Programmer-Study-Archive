# 🤖 AI Programmer Study Archive

Welcome to Rin's personal study archive! This repository contains original notes, hands-on code examples, and practice notebooks created while completing the **AWS AI & ML Scholars Future AWS AI Programmer Nanodegree**.

> **Note:** All notebooks in this repository are original study materials, custom examples, and personal reference guides created to solidify my understanding.

---

## 🐍 Week 1: Python Foundations

**Goal:** Build a practical foundation in core Python syntax, data structures, and exception handling to prepare for AI/ML development.

### 1. Data Types & Conversion
* **Primitive Types:** `int`, `float`, `bool`, `str`
* **Type Inspection:** Use `type()` to verify data types.
* **Type Conversion:** Explicit casting using `int()`, `float()`, `str()`, and `bool()`.

### 2. Slicing & Strings
* **Indexing & Slicing:** Standard `[start:stop]` syntax (inclusive of start, exclusive of stop).
* **String Reversal:** Fast reversal using step slicing: `string[::-1]`.
* **Essential Methods:** `.split()`, `.join()`, `.replace()`, `.find()`, `.count()`, `.startswith()`, `.endswith()`.
* **Formatting:** Variable interpolation using f-strings (`f"Hello, {name}"`).

### 3. Collections Cheat Sheet

| Structure | Ordered? | Mutable? | Duplicates? | Common Use / Syntax |
| :--- | :---: | :---: | :---: | :--- |
| **List** | Yes | ✅ Yes | Yes | Dynamic sequences (`[1, 2, 3]`) |
| **Tuple** | Yes | ❌ No | Yes | Immutable records (`("Rin", 28)`) |
| **Set** | No | ✅ Yes | ❌ No | Unique item collection (`{1, 2, 3}`) |
| **Dictionary** | Yes* | ✅ Yes | Keys unique | Key-Value mappings (`{"key": "value"}`) |

*\*Dictionaries preserve insertion order in modern Python (3.7+).*

#### Key Collection Callouts
* **Single-element Tuple:** Requires a trailing comma, e.g., `(5,)`.
* **Sets:** Key differences between `.remove()` (raises `KeyError`) and `.discard()` (fails silently).
* **Set Math:** Operations include `union()`, `intersection()`, `difference()`, and `symmetric_difference()`.

### 4. Operators & Precision
* **Standard Division (`/`):** Always returns a `float` (e.g., `7 / 2` $\rightarrow$ `3.5`).
* **Floor Division (`//`):** Rounds toward negative infinity (e.g., `7 // 2` $\rightarrow$ `3`).
* **Modulus (`%`):** Calculates remainder.
* **Exponentiation (`**`):** Calculates power.

### 5. Exception Handling & Debugging
Handling expected runtime errors gracefully to prevent pipeline crashes:

* **`ZeroDivisionError`:** Division by zero.
* **`ValueError`:** Operation receives correct type but inappropriate value.
* **`TypeError`:** Incompatible type operations (e.g., `"hello" + 5`).
* **`IndexError`:** Attempting to access an out-of-bounds list index.

---

## 🧠 Bridge to AI: Introductory NLP

Text manipulation in foundational Python lays the groundwork for Natural Language Processing (NLP):

$$\text{Raw Text} \xrightarrow{\text{str methods}} \text{Cleaned Text} \xrightarrow{\text{.split()}} \text{Tokens} \xrightarrow{\text{Analysis}} \text{NLP / Sentiment Analysis}$$

* **Tokenization:** Breaking raw sentences into component words or symbols.
* **Vocabulary Management:** Using `set()` to easily count unique words across documents.
* **Preprocessing:** Standardizing casing with `.lower()` and stripping special characters.

---

## ✅ Week 1 Revision Checklist

- [x] Identify and convert between basic data types (`int`, `float`, `bool`, `str`)
- [x] Master string slicing syntax (`[start:stop:step]`) and f-string formatting
- [x] Know when to use Lists, Sets, Tuples, or Dictionaries
- [x] Perform set mathematical operations (Union, Intersection, Symmetric Difference)
- [x] Apply dictionary methods (`.keys()`, `.items()`, `.pop()`)
- [x] Distinguish between standard division (`/`) and floor division (`//`)
- [x] Implement robust error handling with `try` / `except`
- [x] Tokenize basic text sequences for NLP preparation
