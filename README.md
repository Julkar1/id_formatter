# 🆔 ID Formatter Tool
ID Formatter is a lightweight, browser-based tool for converting and formatting numeric IDs. It supports Bangla → English digit conversion, zero-padding, duplicate cleaning, and exporting the results into multiple formats (TXT split files, Excel, CSV, SQL). No external dependencies—just pure HTML, CSS, and JavaScript running entirely offline. Here the 🔗 Live : https://julkar1.github.io/id_formatter/
<img width="1338" height="871" alt="image" src="https://github.com/user-attachments/assets/df43109a-433c-4bcb-9691-b7be76597bd5" />

A simple, fast, and fully offline web tool that helps you clean, format, and validate large sets of ID (identifier) data with ease.

## 📌 Why This Tool Was Created
In offices, educational institutions, software systems, and databases, it is very common to work with large volumes of ID data. These datasets often contain several issues, such as:
* A mix of Bangla and English digits
* IDs with incorrect length (e.g., 5 digits instead of required 8 digits)
* Extra characters like commas, semicolons, or symbols
* Duplicate IDs appearing multiple times
* The need to export data in TXT / Excel / CSV / SQL formats

The **ID Formatter Tool** was created to solve all of these problems in one place.

👉 With this tool, you can easily:
* Convert Bangla digits to English digits
* Remove unwanted non-numeric characters
* Pad IDs with leading zeros to a fixed length
* Detect duplicate IDs
* Download formatted data in multiple file formats

Most importantly:

* ✔ Works 100% offline
* ✔ No software installation required
* ✔ No internet connection or backend needed

## 🚀 Live (GitHub Pages)
the tool available at:
```
https://julkar1.github.io/id_formatter/
```
## 🧩 Features
* ✔ Bangla → English digit conversion
* ✔ Removal of non-numeric characters
* ✔ Fixed digit padding (leading zeros)
* ✔ Duplicate ID detection
* ✔ TXT file download (with split option)
* ✔ Excel (.xls) download
* ✔ CSV download
* ✔ SQL IN clause generation
* ✔ Copy output to clipboard
* ✔ Mobile-friendly user interface

## 📘 How to Use

### 1️⃣ Set the ID Length

**How many digits? ID length after padding**
Enter the total number of digits each ID should have after formatting.

Example:

* Input: `123`
* Digit Length: `8`
* Output: `00000123`

### 2️⃣ Set Rows Per File

**How many rows will there be in each file**
This option controls how many rows each TXT file will contain when downloading split files.
Example:
* If set to `1000` → a new TXT file will be created after every 1000 rows.

### 3️⃣ Set the Download File Name

**The file name to download is**
The files will be downloaded using the name you provide here.
Example:
```
formatted_id_1.txt
formatted_id_2.txt
```

### 4️⃣ Paste Input Data

In the input box, you can paste data in any of the following formats:
* Line by line
* Comma-separated
* Semicolon-separated
* Bangla or English digits
The tool will automatically clean and normalize the data.

### 5️⃣ Click the Convert Button

When you click **Convert**, the tool will:
* Convert Bangla digits to English
* Remove unwanted characters
* Apply zero-padding based on the selected digit length
* Display the formatted output

### 6️⃣ Check for Duplicate IDs
Click the **Check Duplicate** button to:
* Detect whether any ID appears more than once
* Display duplicate IDs separately
* Show how many times each duplicate appears
This step is especially important before database insertion or official submission.

### 7️⃣ Download or Use the Output
You can:
* **Copy Output** to the clipboard
* Download **TXT (Split)** files
* Download **Excel (.xls)** files
* Download **CSV** files
* Download **SQL IN Clause** format

## 📂 Project Structure
```
index.html   → Complete application (HTML + CSS + JavaScript)
README.md    → Project documentation
```
## 🛠 Technologies Used

* HTML
* CSS
* JavaScript
No frameworks, libraries, or build tools are used.

## 🏁 Conclusion

The **ID Formatter Tool** is a small yet powerful utility that helps you format and validate large volumes of ID data quickly, accurately, and without hassle.
It is highly useful for official work, database operations, and data cleaning tasks.


⭐ If you find this project useful, please consider giving it a star!

