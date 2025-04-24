
# 🛒 Corner Grocery Tracker

A C++ console program that tracks item purchase frequencies for a local grocery store. Users can search for items, view full frequency lists, and visualize purchases through histograms. Data is loaded from a file and saved to a backup for easy reference.

---

## ✨ Features

- 🔍 **Item Search** – Find out how many times an item was purchased.
- 📋 **Frequency List** – View all items with their purchase counts.
- 📈 **Histogram Display** – Visual bar graph using asterisks.
- 💾 **Auto Backup** – Saves item frequencies to `frequency.dat`.

---

## 📂 Input Format

- Input file: `CS210_Project_Three_Input_File.txt`
- Format: One grocery item per line

Example:

Apples Bananas Bananas Carrots Apples
---

## ⚙️ How to Compile & Run

### 🖥️ Requirements

- C++ compiler (e.g., `g++`)
- Console or terminal access

### 🔧 Compile

```bash
g++ -o grocery_tracker "Grocery-Tracking Program.cpp"

Run:
./grocery_tracker

Menu options:
CORNER GROCER ITEM TRACKER
--------------------------
1. Search for an item
2. Display all item frequencies
3. Display histogram of item frequencies
4. Exit

🗂️ File Structure

File Name:                              Purpose:
Grocery-Tracking Program.cpp	          Main source code
CS210_Project_Three_Input_File.txt	    Input: list of purchased items
frequency.dat	                          Output: item frequency backup

Example output:
Enter item to search: Apples
Apples appears 2 time(s).

PURCHASE HISTOGRAM
------------------
Apples       **
Bananas      **
Carrots      *

🚧 Future Improvements:
 Case-insensitive item search
 Add support for custom file names
 Export histogram as text file
 Include timestamps or usage logs

🧠 Author
Sharaine Pestano
Aspiring Software Developer • Healthcare Background • CS Major

🖇️ License
This project is for educational use. No formal license attached.
