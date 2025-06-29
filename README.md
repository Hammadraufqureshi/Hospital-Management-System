# Hospital Management System - Python Tkinter GUI Project
This is a desktop-based Hospital Management System built using Python's Tkinter GUI library. The application allows users to manage patient details and prescriptions, storing data in a CSV file for easy access and record-keeping. It is designed to be a beginner-friendly project for students learning GUI development and basic data handling in Python.

Features
Add, update, delete, and view patient records
Save prescription data with medicine name, dose, and other info
Simple and user-friendly GUI using Tkinter
Data stored locally in a CSV file (hospital_data.csv)
Treeview table to display all patient records
Functional buttons for:
Prescription
Report
Update
Delete
Clear
Exit
Double-click on a table row to auto-fill form fields

🛠 Technologies Used
Component	Description
Python	Main programming language
Tkinter	GUI library for desktop UI
CSV	Used to store patient data
csv.reader()	For reading saved records
csv.writer()	For saving new records
Treeview	For displaying data in a table

📂 File Structure
bash
Copy
Edit
Hospital_Management_System/
│
├── hospital_management.py       # Main source code
├── hospital_data.csv            # Data file (auto-created)
├── README.md                    # Project description
└── screenshots/                 # (Optional) GUI images

🚀 How to Run
Make sure Python is installed (python --version)
Clone the repository or download the .py file
Open terminal or IDLE
Run:
bash
Copy
Edit
python hospital_management.py
The GUI will open and you can begin adding patient information.

