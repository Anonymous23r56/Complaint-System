# RU Complaint System


Welcome to the RU Complaint System, a modern and mobile-friendly platform designed to streamline the complaint management process for students and administrators at Redeemer’s University. This system empowers students to voice their concerns while providing admins with robust tools to manage and resolve complaints efficiently.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


## Key Features

1. User-Friendly Complaint Submission: Students can easily submit complaints using a dedicated form that allows for file attachments, ensuring they can provide all necessary documentation.

2. Comprehensive Admin Panel: Admins benefit from a powerful dashboard that includes login capabilities, detailed analytics, and bulk action options to manage complaints effectively.

3. Role-Based Access Control: The system supports different user roles, allowing full administrators and viewers to access features based on their permissions.

4. Instant Email Notifications: Stay updated with real-time email alerts for new complaints, ensuring timely responses and resolutions.

5. Data Export Options: Admins can export filtered complaints in CSV or PDF formats for further analysis or record-keeping.

6. Responsive Design: The system features a dark mode and is fully responsive, providing a seamless experience across all devices.

7. Robust Input Validation: Both frontend and backend input validation ensure data integrity and security.

## Getting Started

Prerequisites


To set up the RU Complaint System, ensure you have the following installed:
- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/ru-complaint-system.git
   cd ru-complaint-system
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your email config in `config.py` (use your Gmail and app password).

4. Run the app:
   ```
   python app.py
   ```

5. Open your browser and go to `http://127.0.0.1:5000/`


### Default Admin Login

- Username: `admin`
- Password: `RUNSA2025`

## Usage

- Students can submit complaints via the form.
- Admins can log in at `/admin` to view, resolve, delete, and export complaints.

  

 # 🛠️ Tech Stack

- **Backend:** Flask, Flask-Mail, SQLite, ReportLab
- **Frontend:** Bootstrap 5, Chart.js, HTML5, CSS3, JavaScript
- **Other:** Responsive design, dark mode, secure file uploads

---

## 📈 Why This Project?

- **For Students:**  
  A simple, transparent way to report issues and track complaint status.

- **For Admins:**  
  A powerful, data-driven tool to manage, resolve, and analyze complaints—improving campus life.

---

## Contributing
- We welcome contributions! If you have suggestions for major changes, please open an issue to discuss your ideas before submitting a pull request.

## 📄 License

This project is licensed under the [MIT License](LICENSE).



Feel free to modify any sections or details to better fit your vision!
