# Basta-Fazoolin
🍝 Basta Fazoolin' with My Heart
A fictional Italian restaurant management system designed to simulate real-world business data handling. This project models menus, franchises, and businesses using object-oriented programming principles in Python.

📁 Project Structure
bash
Copy
Edit
.
├── restaurant.py             # Main implementation (Menu, Franchise, Business classes)
├── test_basta_fazoolin.py   # Unit tests using unittest
└── README.md                 # Project overview and documentation
✅ Features
Menu Management: Create and manage multiple menus with items and availability times.

Franchise System: Assign menus to different restaurant locations.

Business Logic: Simulate customer interactions such as retrieving available menus and calculating bills.

Time-based Queries: Dynamically fetch menus based on the current time.

🧠 Concepts Used
Object-Oriented Programming (OOP)

Python datetime.time for schedule handling

Data structures:

dict for storing menu items and prices

list for managing collections of menus and franchises

🛠️ How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/basta-fazoolin.git
cd basta-fazoolin
2. Run the Application
bash
Copy
Edit
python restaurant.py
3. Run Unit Tests
bash
Copy
Edit
python -m unittest test_basta_fazoolin.py
🧪 Example Output
bash
Copy
Edit
Brunch menu available from 11:00 AM to 04:00 PM
Brunch bill: 19.5

Available menus at 4:30 PM:
 - Brunch
 - Early Bird

Business franchises:
 - 123 Fazoolin' Street
 - 456 Pasta Lane
🧪 Sample Code Usage
python
Copy
Edit
brunch = Menu("Brunch", {"pancakes": 7.50, "coffee": 1.50}, time(11, 0), time(16, 0))
print(brunch.calculate_bill(["pancakes", "coffee"]))  # Output: 9.0


No external libraries required

