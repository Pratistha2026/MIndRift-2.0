# MIndRift-2.0

# SpendSmart – Personal Finance Companion

SpendSmart is a personal finance management app designed to help users track expenses, monitor spending habits, and manage their budgets with ease. With intelligent insights, visual reports, and goal-based tracking, SpendSmart empowers users to build better financial habits and improve their financial awareness.

---

## Project Idea

SpendSmart is a personal finance companion designed to help users track their daily expenses, monitor spending patterns, and manage budgets effectively. The app provides goal tracking, data-driven insights, and personalized financial recommendations to help users build better money habits and improve their financial literacy.

---

## Tech Stack

### Frontend
- **React.js** – User interface framework
- **React Router** – Client-side routing
- **Axios** – HTTP client for API requests
- **CSS / TailwindCSS** – Styling and responsive design

### Backend
- **Node.js** – Server runtime environment
- **Express.js** – Backend framework
- **Mongoose** – MongoDB object modeling
- **bcrypt** – Password hashing and security
- **JWT** – Authentication and authorization

### Database
- **MongoDB** – NoSQL database (Local / MongoDB Atlas)

### Tools & Environment
- **VS Code** – Code editor
- **Git & GitHub** – Version control
- **Postman / Thunder Client** – API testing
- **npm** – Package manager

---

## Features

### 1. User Registration & Login (Authentication)
- Secure user signup and login functionality
- Password hashing using bcrypt for enhanced security
- JWT-based authentication for session management
- User data stored securely in MongoDB

### 2. Add Transactions
Users can quickly record:
- **Income** – Money earned
- **Expenses** – Money spent
- **Categories** – Transaction classification
- **Amount** – Numerical value
- **Description** – Transaction details
- **Date** – When the transaction occurred

### 3. View All Transactions
- Displays a complete, organized list of all recorded transactions
- Real-time data fetching from MongoDB
- Easy-to-scan transaction history

### 4. Categorized Spending
- Each transaction entry includes a category (Food, Travel, Bills, Shopping, Entertainment, etc.)
- Helps users understand spending patterns and where their money goes
- Enables better budget planning and expense awareness

### 5. Dashboard Overview
The dashboard provides a comprehensive financial snapshot:
- **Total Income** – Cumulative earnings
- **Total Expense** – Cumulative spending
- **Current Balance** – Net financial position
- **Recent Transactions** – Quick access to latest activity

### 6. Visual Charts & Graphs
- **Pie Chart** – Visual breakdown of spending by category
- **Monthly Expense Graph** – Line and bar charts tracking spending trends over time
- Helps users visualize financial patterns and identify spending anomalies

---

## How to Run the Project

### Backend Setup

```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install
```

Create a `.env` file inside the `backend` directory with the following variables:

```env
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend server:

```bash
npm run dev   # if using nodemon for auto-reload
# or
node server.js
```

**Backend runs on:** `http://localhost:5000`

---

### Frontend Setup

```bash
# Open another terminal and navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm start
```

**Frontend runs on:** `http://localhost:3000`

---

## Screenshots

```
/spend smart ss/
├── ss1.png
├── ss2.png
├── ss3.png
├── ss4.png
└── ss5.png
└── ss6.png
└── ss7.png
```

---

## Demo Video Link

Watch a complete walkthrough of SpendSmart features and functionality:

[SpendSmart Demo Video](https://drive.google.com/file/d/1gizPze4EaWunOZSqDhhvYBOHaocfOgbd/view?usp=drive_link)

---

## Team Members & Roles

| Name | Role |
|------|------|
| Nikita Bhardwaj | Project Lead & Documentation Head |
| Piyush Singh Shahi | Full Stack Developer |
| Pratistha Singh | Project Manager |
| Divyanshu Rawat | Deployment Engineer |
| Himanshu Kushwaha | UI Designer |

---

## Installation & Setup Summary

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd spendsmart
   ```

2. **Setup MongoDB**
   - Use MongoDB Atlas for cloud-based or local MongoDB instance
   - Obtain connection string and add to `.env` file

3. **Install dependencies for both frontend and backend**
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. **Start the application**
   - Open two terminal windows
   - Terminal 1: `cd backend && npm run dev`
   - Terminal 2: `cd frontend && npm start`

5. **Access the application**
   - Open your browser and navigate to `http://localhost:3000`

---

## Future Enhancements

- Mobile app version (React Native)
- Advanced analytics and forecasting
- Budget alerts and notifications
- Expense receipts and attachments
- Multi-currency support
- Collaborative budgeting for families
- Integration with banking APIs

---

## License

This project is open source and available for educational purposes.

---

