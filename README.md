

# **Students Grievance Management System**

**Overview:**
The *Students Grievance Management System* is a web-based platform designed to streamline the process of managing and addressing grievances raised by students in an educational institution. The system allows students to submit grievances under various categories, and the administration can review and address them efficiently.

**Key Features:**
- **User Login System:** Students and administrators can log in securely with unique credentials.
- **Category-Based Grievance Submission:** Students can submit grievances under predefined categories (e.g., academic, non-academic, hostel, etc.).
- **Real-Time Updates:** Students can track the status of their grievances in real-time.
- **Admin Dashboard:** The admin can view all submitted grievances, filter them by category, and mark them as resolved or under review.
- **Responsive Design:** The system is designed to be mobile-friendly and easily accessible on various devices.
- **Database-Driven:** All grievance data is stored in a MySQL database, ensuring data integrity and ease of access.

**Technologies Used:**
- *Front-End:* HTML, CSS, JavaScript
- *Back-End:* PHP
- *Database:* MySQL
- *Additional Tools:* Bootstrap for responsive design, Gulp for automating tasks.

**System Architecture:**
- **Student Module:**
  - Allows students to submit grievances by logging in.
  - Students can categorize their grievances and provide detailed descriptions.
  - The status of the grievance can be viewed in the user dashboard at [*localhost/cms/user/index.php*](http://localhost/cms/user/index.php).
  
- **Admin Module:**
  - Admins can manage grievances, assign them to relevant departments, and track their resolution.
  - A dashboard displaying unresolved, resolved, and under-review grievances can be accessed at [*localhost/cms/admin/index.php*](http://localhost/cms/admin/index.php).

**File Descriptions:**
- **index.php:** Handles the main dashboard and logic for the student grievance submission.
- **index.css:** Contains the styling for the front-end user interface.
- **gulpfile.js:** Automates front-end tasks such as CSS minification and JavaScript linting.
- **cms.sql:** Database schema for the grievance system, including student records, grievance categories, and logs of submissions and resolutions.

**How to Run:**
1. Clone the repository to your local machine.
2. Import the *cms.sql* file into your MySQL database.
3. Update the database connection details in the *config.php* file.
4. Start the local server using XAMPP, WAMP, or any other server environment.
5. Navigate to the *index.php* page to start using the system:
   - User module: [*localhost/cms/user/index.php*](http://localhost/cms/user/index.php)
   - Admin module: [*localhost/cms/admin/index.php*](http://localhost/cms/admin/index.php)
