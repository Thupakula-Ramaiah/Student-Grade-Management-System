# Student-Grade-Management-System
simple Python-based console application to manage student records and grades efficiently.
The system allows users to add, view, update, delete students, and analyze grade statistics, with persistent data storage using JSON.

📌 Features
➕ Add students with multiple grades
📋 View all students with their grades and average score
✏️ Update student grades
❌ Delete student records
📊 View overall statistics (average, highest, lowest grade)
💾 Persistent storage using students.json

🛠️ Tech Stack
Python 3
JSON (File-based data storage)

📁 Project Structure
Student-Grade-Management-System/
│
├── main.py          # Main Python program
├── students.json    # Stores student data (auto-generated)
└── README.md        # Project documentation

▶️ How to Run

Clone the repository
git clone https://github.com/Thupakula-Ramaiah/Student-Grade-Management-System.git
Navigate to the project folder
cd Student-Grade-Management-System

Run the program
python main.py

📖 Menu Options
1. Add Student
2. View All Students
3. Update Student Grades
4. Delete Student
5. Show Statistics
6. Exit

📊 Statistics Calculated
✅ Average grade of all students
🔼 Highest grade
🔽 Lowest grade
💾 Data Storage

Student data is saved in students.json
Data is automatically loaded when the program starts
Changes are saved after every operation

⚠️ Important Notes
Grades must be entered as numeric values separated by spaces
Student names are case-sensitive
Ensure valid input to avoid runtime errors

🚀 Future Improvements
Input validation and error handling
Search students by name
Student ranking system
GUI-based interface (Tkinter / Web app)

👩‍💻 Author
T.Ramaiah
B.Tech – Electronics and Communication Engineering
