# Helping a Friend (Beginner C Problem)

**For Practicing Purposes**  
This is a small C program I made during vacation to help a friend practice basic programming concepts from **Computer Programming 1**.  
It also serves as my personal review of past lessons such as **string handling**, **functions**, **loops**, and **bubble sort**.

---

## The program:
1. Accepts five names from the user.
2. Validates that each name contains no numbers.
3. Sorts the names alphabetically (a–z) using **Bubble Sort**.
4. Displays the sorted list.

---

## What it contains?
- **Input validation** → Ensures names do not contain numbers (`checkname` function).
- **Alphabetical sorting** → Implemented with **Bubble Sort** in the `sortNames` function.
- **String manipulation** → Uses `strcmp()` and `strcpy()` for comparing and swapping strings.
- **Looping until valid input** → Keeps asking until a proper name is entered.

---

## Code Overview

### Functions
- `int checkname(char pangalan[])`  
  Checks if the name contains any numeric digits. Returns:
  - `1` if invalid (contains numbers)
  - `0` if valid

- `void sortNames(char names[5][100])`  
  Sorts the array of names alphabetically using **Bubble Sort**.

---

## Sample Run

![Program Screenshot](ss1.jpeg)
