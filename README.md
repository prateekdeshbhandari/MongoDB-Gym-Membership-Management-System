# MongoDB Gym Membership Management System

A modern web-based gym membership management system built with Flask and MongoDB. 

## Project Structure

```
Gym membership/
├── gymmember.py          # Main Flask application
└── templates/            # HTML templates
    ├── index.html        # Dashboard (main page)
    ├── login.html        # Admin login page
    ├── view_member.html  # Member details page
    └── members_by_plan.html  # Filtered members view
```

## Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.7+** - [Download Python](https://www.python.org/downloads/)
- **MongoDB** - [Download MongoDB](https://www.mongodb.com/try/download/community)
- **pip** - Python package manager (usually comes with Python)

## Installation

### Step 1: Install MongoDB

1. Download and install MongoDB Community Edition from the official website
2. Start MongoDB service:
   - **Windows**: MongoDB should start automatically as a service
   - **Linux/Mac**: Run `sudo systemctl start mongod` or `brew services start mongodb-community`

### Step 2: Install Python Dependencies

1. Navigate to the project directory:
   ```bash
   cd "MongoDB-Gym-Membership-Management-System-main/Gym membership"
   ```

2. Install required packages:
   ```bash
   pip install flask pymongo werkzeug
   ```

   Or create a `requirements.txt` file with:
   ```
   Flask==2.3.0
   pymongo==4.5.0
   Werkzeug==2.3.0
   ```
   
   Then install:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run

### Step 1: Start MongoDB

Ensure MongoDB is running on `localhost:27017` (default port).

**Windows:**
- MongoDB usually runs as a Windows service automatically
- Verify: Open Services and check if "MongoDB" service is running

**Linux/Mac:**
```bash
sudo systemctl start mongod
# or
mongod
```

### Step 2: Run the Application

1. Navigate to the project directory:
   ```bash
   cd "MongoDB-Gym-Membership-Management-System-main/Gym membership"
   ```

2. Run the Flask application:
   ```bash
   python gymmember.py
   ```

3. Open your web browser and visit:
   ```
   http://localhost:5000
   ```

## Default Login Credentials

- **Username**: `admin`
- **Password**: `admin123`

**⚠️ Important**: Change the default password in production!

## Usage Guide

### Login
1. Access the application at `http://localhost:5000`
2. You'll be redirected to the login page
3. Enter admin credentials to access the dashboard
<img width="1144" height="834" alt="image" src="https://github.com/user-attachments/assets/dc952c50-de3b-45b9-a171-44fad33cc633" />

### Add a New Member
<img width="1588" height="856" alt="image" src="https://github.com/user-attachments/assets/16c08f9c-6e94-40bf-aca9-fa2bf3855831" />



### View Members
- All members are displayed in a table with:
  - Member ID, Name, Age, Contact
  - Subscription plan and dates
  - Membership status (Active/Expired)
  - Action buttons (View, Update, Delete)
<img width="1509" height="738" alt="image" src="https://github.com/user-attachments/assets/31cc3d5f-316b-443e-9d36-bdfd77c3a49c" />

### Manage Expired Memberships
<img width="1739" height="682" alt="image" src="https://github.com/user-attachments/assets/7980e340-a8c1-4b5d-bfc0-76c63b883c3d" />

### MongoDB Connection 
<img width="1767" height="733" alt="image" src="https://github.com/user-attachments/assets/65f65eba-0261-40d6-8d06-76ba2d70738d" />


## Technologies Used

- **Backend**: Flask (Python web framework)
- **Database**: MongoDB (NoSQL database)
- **Frontend**: HTML5, CSS3, JavaScript
- **Authentication**: Werkzeug password hashing

**Need Help?** 
contact :<br>
name: Prateek G Deshbhandari<br>
gmail: deshbhandariprateek7@gmail.com<br>
