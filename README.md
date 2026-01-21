📜 Certificate Generation Automation (Python)
 Overview

This Python script automatically generates personalized certificates from an Excel workbook.

For each participant:

The name is read from Excel

The name is centered and printed on a certificate template

A PNG image is generated

The image is converted into a PDF

Files are neatly organized into folders

This is ideal for:

Events & workshops

Colleges & clubs

Hackathons & seminars

ACM / IEEE / student chapters

🧩 Features

✅ Reads participant data from Excel (.xlsx)
✅ Automatically creates folders
✅ Writes names on certificate image
✅ Centers text dynamically
✅ Converts certificates to PDF
✅ Generates one image + one PDF per participant
✅ Works completely offline

🛠️ Technologies Used

Python 3

Pillow (PIL) – Image processing

img2pdf – Image → PDF conversion

openpyxl – Excel file handling

tkinter – File selection dialog


![Uploading image.png…]()



⚙️ Installation (A–Z Step by Step)
1️⃣ Install Python

Download and install Python 3.8 or above
👉 https://www.python.org/downloads/

✔️ Make sure “Add Python to PATH” is checked

2️⃣ Clone or Download Project
git clone <your-repo-link>


OR
Download ZIP and extract it

3️⃣ Install Required Libraries

The script auto-installs dependencies, but you can manually install them:

pip install img2pdf openpyxl pillow

4️⃣ Required Files (Must Have)

Place these files in the same folder as the script:

certificates.png → Certificate background

Lora-Bold.ttf → Font file

Excel workbook (.xlsx)

 ##### Automated-Certificate-Generation-System-Using-Python
