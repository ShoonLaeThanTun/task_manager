# Modern Task Manager

A sleek and modern task management application built with Flask, featuring a beautiful UI and intuitive task organization system.

## Features

- **User Authentication**
  - Secure registration and login system
  - Password hashing for security
  - Session management

- **Task Management**
  - Create, read, update, and delete tasks
  - Organize tasks by status (To Do, In Progress, Done)
  - Categorize tasks (Personal, Work, Urgent)
  - Set due dates for tasks
  - Track task creation dates

- **Modern UI/UX**
  - Clean and responsive design
  - Intuitive icon-based actions
  - Status-based task organization
  - Beautiful hover effects and transitions
  - Mobile-friendly layout

## Technology Stack

- **Backend**: Flask (Python)
- **Database**: SQLAlchemy
- **Authentication**: Flask-Login
- **Frontend**: HTML, CSS, JavaScript
- **Icons**: Font Awesome
- **UI Framework**: Bootstrap

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/callmeHeinHtet/task-manager.git
   cd task-manager
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   
   # On Windows
   .\venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory and add:
   ```
   SECRET_KEY=your_secret_key_here
   ```

5. Initialize the database:
   ```bash
   python
   >>> from app import app, db
   >>> with app.app_context():
   >>>     db.create_all()
   >>> exit()
   ```

6. Run the application:
   ```bash
   python app.py
   ```

7. Access the application at `http://localhost:5000`

## Usage

1. **Register/Login**: Create an account or login to access your tasks
2. **Create Tasks**: Click the "New Task" button to create a task
3. **Manage Tasks**: 
   - Click the play icon (▶️) to move a task to "In Progress"
   - Click the check icon (✓) to mark a task as "Done"
   - Click the edit icon (✏️) to modify task details
   - Click the delete icon (🗑️) to remove a task
4. **Organize**: Use categories and due dates to keep tasks organized

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request


## Acknowledgments

- Flask documentation and community
- Bootstrap framework
- Font Awesome icons 
