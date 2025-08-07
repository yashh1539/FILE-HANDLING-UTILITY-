# File Handling Utility (Java)

This is a little utility I wrote in Java to play with **file reading, writing, and modifying**. It’s basic, but it works well if you want to do stuff like edit files or automate simple file tasks without pulling in libraries.

### 📦 What it can do:
- Read files and show the contents
- Write or append text into files
- Replace or update lines of text inside a file

### 🧱 Breakdown of files:
- `FileReaderUtil`: Reads file line by line
- `FileWriterUtil`: Writes or appends text
- `FileModifierUtil`: Does the actual modifying and replacing
- `Main`: Puts it all together — you can tweak it to test different functions

### 🧰 Built with:
- Core Java only (`java.io.*`, `java.nio.file.*`)
- No libraries, no dependencies

### 🚀 To run:
Clone the project, open it in your IDE, and run `Main.java`. You can modify the file paths and text to test various things.

---

Honestly, this was a fun way to sharpen my file I/O skills and better understand how things like `BufferedReader`, `FileWriter`, and file manipulation work in Java.
