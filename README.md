# Student_and_staff_complaint_management_system
A Streamlit-based complaint management system for students and staff.

## 📌 Overview
The **Student & Staff Feedback and Complaint Management System** is a digital solution designed to streamline the process of collecting, categorizing, tracking, and resolving feedback and complaints across various departments within an educational institution. This system enhances transparency, improves communication between stakeholders, and ensures prompt resolution of concerns.

## 🔥 Key Features
- **User Authentication**: Secure login for students, staff, and administrators.
- **Role-Based Access**: Different access levels for students, staff, and administrators.
- **Feedback & Complaint Submission**: Users can submit feedback and complaints through a structured form.
- **Categorization & Prioritization**: Complaints are categorized and prioritized based on severity.
- **Real-Time Tracking**: Users can monitor the status of their complaints.
- **Admin Dashboard**: Provides a comprehensive view of active complaints, resolved issues, and response efficiency.
- **Automated Notifications**: Users receive status updates on their complaints.
- **Data Analytics**: Insights on frequently reported issues and department performance.

## 🏗️ Tech Stack
### **Frontend:**
- Streamlit (for UI development)

### **Backend:**
- Python (with Streamlit for web framework)

### **Database:**
- Firebase / MySQL / MongoDB (as per project requirements)

### **Authentication & Security:**
- Role-based access control

### **Hosting & Deployment:**
- Local deployment using Streamlit

## 🚀 How It Works
1. **User Registration & Authentication**
   - Students and staff log in securely.
   - Role-based authentication ensures proper access control.

2. **Submitting Complaints & Feedback**
   - Users fill out a structured form, selecting complaint categories and priorities.
   - Submissions are stored securely in the database.

3. **Tracking & Resolution**
   - Admins categorize, prioritize, and assign complaints to the concerned departments.
   - Users receive notifications on status changes.

4. **Dashboard & Analytics**
   - Admins access a real-time dashboard with complaint statistics and trends.
   - Data visualization tools help improve institutional policies.

## 🛠️ Installation & Setup
### **Prerequisites:**
- Python (3.x)
- Firebase/MySQL/MongoDB setup (optional)

### **Steps to Set Up Locally:**
1. Clone the repository:
   ```sh
   git clone https://github.com/RenukaK1404/Student_and_staff_complaint_management_system.git
   cd Student_and_staff_complaint_management_system
   ```
2. Install dependencies:
  ```sh
   pip install streamlit pandas matplotlib
  ```
   Additionally, if you're missing any libraries, install them separately:
   ```sh
   pip install streamlit pandas matplotlib hashlib datetime os io re
   ```
3. Set up database configuration in `.env` file.
4. Run the Streamlit application:
   ```sh
   streamlit run "file_path"
   ```
5. Open the provided URL in a browser.
6. Access the dashboard and test the complaint submission workflow.

## 📦 Requirements (`requirements.txt`)
```plaintext
streamlit
pandas
numpy
firebase-admin  # If using Firebase
mysql-connector-python  # If using MySQL
pymongo  # If using MongoDB
```

## 📌 License
This project is open-source and free to use.

