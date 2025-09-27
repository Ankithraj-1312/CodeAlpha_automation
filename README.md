# CodeAlpha_automation
# 🖼️ JPEG File Organizer

A simple Python script to automatically move all `.jpg` files from the current working directory into a new folder called **`jpegs_moved`**.

## 🚀 Features

* Scans the current directory for `.jpg` files.
* Creates a new folder named `jpegs_moved` if it doesn’t already exist.
* Moves all `.jpg` files into that folder.
* Prints progress updates while running.

## 📂 Project Structure

```
ImageMover/
│── mover.py         # The main script
│── README.md        # Documentation
│── jpegs_moved/     # (Created automatically when the script runs)
```

## ▶️ How to Run

1. Clone or download this repository.

   ```bash
   git clone https://github.com/YourUsername/ImageMover.git
   cd ImageMover
   ```

2. Run the script in your terminal or VS Code:

   ```bash
   python mover.py
   ```

3. After running, check the new folder:

   ```
   jpegs_moved/
   ```

   It will contain all `.jpg` files from the original directory.

## 📝 Example Output

```
Created folder: jpegs_moved
Moved: photo1.jpg
Moved: sample.jpg
Task completed ✅
```

## ⚡ Requirements

* Python 3.x
* No external libraries required (uses only built-in modules).

## 📌 Notes

* Only `.jpg` files are moved (not `.jpeg` or `.png`).
* Run the script in the folder where your images are stored.
* The script is safe and will **not delete** any files, just moves them.

---

Made with ❤️ using Python.
