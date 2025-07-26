# Attendance Management System

The Attendance Management System is a comprehensive web-based solution designed to streamline and automate the process of tracking student attendance in educational institutions. The system provides separate interfaces for teachers and students, making it easy to manage and monitor attendance records efficiently.

## Features

### For Teachers
- 📝 Mark and manage student attendance with time slot options
- 📊 Generate comprehensive attendance reports with filtering capabilities
- 👥 Manage student records and view enrolled students
- 📈 View attendance statistics and analytics
- 📚 Manage student marks with different exam types (internal, midterm, final)
- ⚙️ Update profile settings and change password
- 🔒 Secure login system

### For Students
- 👀 View personal attendance records across all enrolled courses
- 📊 Access attendance statistics and performance analytics
- 📱 User-friendly interface optimized for all devices
- 📚 View course enrollment status and attendance percentages
- 🔐 Secure login system using USN and DOB

## Screenshots

### Home Page
![home page](https://github.com/user-attachments/assets/a18956e5-cc1b-4b7a-866a-19c3fd4b1e41)



### Login Page
![teacher login](https://github.com/user-attachments/assets/be8d391a-7c9a-4923-98a5-4e1255b4a1a9)
![student login](https://github.com/user-attachments/assets/4fde8ddc-4456-40a7-af94-3bee300f0da1)


### Teacher Dashboard
![teacher dashboard](https://github.com/user-attachments/assets/a47ce0d6-a64a-441b-8748-e489039051d3)
![marks attendence](https://github.com/user-attachments/assets/c5ef7333-5503-45fc-bb4c-d3905f3f78d0)
![view attendence](https://github.com/user-attachments/assets/2e3a977c-e7a1-476b-af66-9faa9643c4a5)
![list of student](https://github.com/user-attachments/assets/fb526257-25b0-4fd7-8439-5f32224fd552)
![manage marks](https://github.com/user-attachments/assets/4514d663-6237-4cd6-9a90-5d2d5429cb6a)

### Student Dashboard
![student dashboard](https://github.com/user-attachments/assets/1cdc9ad7-d8bb-4c79-81f8-7ddeb7d86153)
![student view attendence](https://github.com/user-attachments/assets/992e1419-8cc0-4ae3-8723-4c3101a85271)




## Technology Stack

- **Frontend:**
  - HTML5
  - CSS3
  - Bootstrap 5
  - Font Awesome (for icons)
  - JavaScript

- **Backend:**
  - PHP
  - MySQL

## Database Schema

The system uses the following main tables:

- **students**: Stores student information (id, full_name, usn, email, phone, dob, class, section)
- **teachers**: Manages teacher data (id, full_name, email, password, employee_id, department)
- **courses**: Contains course details (id, course_code, course_name, semester)
- **attendance**: Records attendance data (student_id, course_id, date, time_slot, status)
- **student_courses**: Maps students to enrolled courses
- **teacher_courses**: Maps teachers to assigned courses
- **subject_marks**: Stores academic performance data



## Directory Structure

```
attendence1/
├── assets/          
├── config/         
├── includes/        
├── student/         
├── teacher/         
├── index.php        
├── student_login.php
├── teacher_login.php
└── attendance_system.sql
```

## Usage

1. **Teacher Login:**
   - Access the teacher portal using your credentials
   - Manage attendance records
   - Generate reports
   - View student statistics

2. **Student Login:**
   - Access the student portal using your credentials
   - View personal attendance records
   - Check attendance statistics

## Security Features

- Secure login system
- Password encryption
- Session management
- Input validation
- SQL injection prevention

## Acknowledgments

- Bootstrap for the frontend framework
- Font Awesome for the icons
- All contributors who have helped in the development of this system

## Contributors
👥 Project Team
 - Vishnu PS
 - Vishwanath
 - Vikas

## License
This project is licensed under the MIT License - see the [MIT License](LICENSE) file for details.
