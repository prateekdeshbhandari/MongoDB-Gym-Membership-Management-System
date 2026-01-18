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
![alt text](image.png)
### Add a New Member
![alt text](image-1.png)

### View Members
- All members are displayed in a table with:
  - Member ID, Name, Age, Contact
  - Subscription plan and dates
  - Membership status (Active/Expired)
  - Action buttons (View, Update, Delete)
![alt text](image-2.png)


### Manage Expired Memberships
![alt text](image-3.png)
### MongoDB Connection 
![alt text](image-4.png)

## Technologies Used

- **Backend**: Flask (Python web framework)
- **Database**: MongoDB (NoSQL database)
- **Frontend**: HTML5, CSS3, JavaScript
- **Authentication**: Werkzeug password hashing

**Need Help?** 
contact :
name: Prateek G Deshbhandari
gmail: deshbhandariprateek7@gmail.com
