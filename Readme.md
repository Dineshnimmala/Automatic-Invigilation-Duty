

# Automation in Invigilation Duty

The Automatic Invigilation Duty Assignment System is designed to automate the process of assigning invigilation duties for examinations. This system streamlines the task allocation process, ensuring fair distribution of responsibilities among staff members, while considering factors like availability, preferences, and workload balance..

## Prerequisites
Before you begin, ensure you have the following installed:
- **Python 3.x**: [Download Python](https://www.python.org/downloads/)
- **WAMP/XAMPP Server**: [Download WAMP](https://www.wampserver.com/) or [Download XAMPP](https://www.apachefriends.org/index.html)
- **MySQL Connector**: Installable via `pip`.

## Installation and Setup

### Step 1: Clone the Repository
Clone the project repository to your local system using the following command:

git https://github.com/Dineshnimmala/Automatic-Invigilation-Duty.git

### Step 2: Move the Folder
Move the folder `Automatic-Invigilation-Duty` to the appropriate directory:
- For **WAMP**: Move it to `www`.
- For **XAMPP**: Move it to `htdocs`.

### Step 3: Start WAMP/XAMPP Server
Launch your WAMP or XAMPP server to enable local hosting.

### Step 4: Set Up the Database
1. Open the **phpMyAdmin** interface provided by your WAMP/XAMPP server.
2. Create a new database for the project.
3. Update the database connection details in the `config.py` file:
   ```python
   DATABASE = {
       'host': 'localhost',
       'user': 'your_username',
       'password': 'your_password',
       'database': 'your_database_name'
   }
   ```

### Step 5: Install MySQL Connector
Install the required MySQL connector library:
```bash
pip install mysql-connector
```

### Step 6: Run the Application
Run the main Python script to start the mail automation feature:
```bash
python main.py
```

### Step 7: Access the Portal
Open your web browser and navigate to:
```
http://localhost/Automatic-Invigilation-Duty
```

## Features
- **Mail Automation**: Streamlines communication for invigilation duties.
- **Database Integration**: Efficient data storage and retrieval using MySQL.
- **User-Friendly Interface**: Easily accessible portal for all users.

## Troubleshooting
- Ensure the WAMP/XAMPP server is running when accessing the portal.
- Verify the database credentials in `config.py` are correct.
- Confirm Python and required libraries are installed properly.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


