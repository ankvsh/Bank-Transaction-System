🏦 Bank Transaction System (Ledger-Based Backend)

A production-style backend system that simulates how real banking systems handle transactions, balances, and data consistency using a ledger-based approach.

Built with Node.js, Express, and MongoDB, this project demonstrates secure authentication, account management, and reliable transaction processing.

🚀 Features
🔐 Authentication & Security
User Registration & Login
Password hashing using bcrypt
JWT-based authentication
Protected routes with middleware
💳 Account Management
Create and manage user accounts
Account status validation
Secure access control
💸 Transaction System
Credit & Debit transactions
Transaction states (Pending → Completed)
Idempotency handling (prevents duplicate transactions)
📒 Ledger System (Core Feature)
Every transaction is recorded in a ledger
Balance is derived dynamically (not stored directly)
Ensures data consistency and auditability
📊 Advanced Backend Concepts
MongoDB Aggregation Pipeline
Idempotency validation
Middleware-based architecture
Scalable folder structure
📧 Notifications
Email notifications using Nodemailer
Alerts for transactions and user actions
🛠️ Tech Stack
Node.js
Express.js
MongoDB
Mongoose
JWT (Authentication)
bcrypt (Password hashing)
Nodemailer (Emails)
Cookie-parser
📁 Project Structure
src/
 ├── config/
 ├── controllers/
 ├── middleware/
 ├── models/
 ├── routes/
 └── services/
server.js
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/ankvsh/Bank-Transaction-System.git
cd Bank-Transaction-System
2️⃣ Install dependencies
npm install
3️⃣ Create .env file
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
4️⃣ Run the server
npm run dev
🧪 API Testing

Use Postman or any API client to test:

Auth APIs (Register/Login)
Account APIs
Transaction APIs
Balance fetching
🧠 Key Learning Outcomes
Real-world backend architecture
Ledger-based financial systems
Secure authentication flows
Handling concurrency & idempotency
Writing scalable and maintainable APIs
