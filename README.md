Expense Management System
💸 A Java Swing GUI application with MySQL integration for tracking personal finances.

Core Features
1. User Authentication
🔐 Secure Login/Logout with username & password

📝 New User Registration with validation

👤 User-Specific Data Isolation (each user sees only their expenses)

2. Expense Management
➕ Add Expenses (category, amount, date, description)

👀 View Expenses in a tabular format

✏️ Edit Existing Expenses (update details)

❌ Delete Expenses with confirmation

🔍 Filter Expenses by:

📅 Date (Daily/Monthly/Yearly)

🏷️ Category (Food, Transport, etc.)

💰 Amount Range

3. Reporting & Analytics
📊 Daily/Monthly Summaries (visual charts)

🗂️ Category-Wise Breakdown (pie/bar charts)

📤 Export Reports to PDF/Excel

4. Admin Dashboard (Optional)
👥 Manage Users (view/delete accounts)

📉 System Analytics (total users, expenses, etc.)

Technical Highlights
Frontend: Java Swing (GUI)

Backend: MySQL Database

Security: Password protection (hashing in production)

Validation: Input checks for amounts/dates

How to Run
Setup MySQL with provided schema.

Update DBConnection.java with your credentials.

Launch LoginForm.java to start.

Future Enhancements
📱 Mobile Sync (Android app)

💳 Bank Integration (auto-import transactions)

🔔 Budget Alerts (spending limits)

Why This Project?
Ideal for Java learners to practice GUI + database integration

Demonstrates clean architecture (MVC pattern)

Ready-to-use for personal finance tracking
