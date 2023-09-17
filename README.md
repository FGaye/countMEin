# Attendance Management System with Device-Student Verification

**Backend Technologies:** C# .NET 7 with Entity Framework

**Frontend Technologies:** React 18, React Router DOM, Vite, and TypeScript

## Key Features

1. **Lecturer Signup:**
   - Lecturers can register to oversee student attendance.

2. **QR Code Generation:**
   - Lecturers can create QR codes valid for the specified class session duration.

3. **QR Code Display:**
   - Display the generated QR code for student scanning.

4. **Student Login:**
   - Students scan the QR code and log in using their student email.

5. **Student Information Collection:**
   - Capture student information, including:
     - First name
     - Last name
     - Email address
     - Device identifier

6. **Duplicate Prevention:**
   - Ensure one device records attendance for a unique student to prevent duplicates.

7. **Attendance Collection:**
   - Record attendance data.

8. **Notifications:**
   - Notify students of their recorded attendance.
   - Notify the event organizer of new attendees.

**Additional Requirements:**

1. **QR Code Validity:**
   - QR codes are valid only during the class session, regenerating automatically every 30 seconds.

**To-Do List:**

1. - [x] **Project Setup (Backend)**
1. - [x] **Client App Development (UI Implementation and Design)**
1. - [x] **API Integration using Axios**
1. - [x] **Forms Implementation and Validation with React Hook Form and Yup**
1. - [ ] **Google Login Integration**
1. - [x] **User (Host) Registration and Login**
1. - [ ] **Guest Attendance Management and QR Code Regeneration**
1. - [ ] **Pagination, Sorting, and Filtering Implementation**
1. - [ ] **Export Functionality for Attendee Data in PDF, Excel, or CSV**
1. - [ ] **Exception Handling and Error Management**
1. - [ ] **Initial Staging Version Deployment**
1. - [ ] **UI Enhancement**
1. - [ ] **Conversion to a Progressive Web App (PWA)**
1. - [ ] **Final Polish and Cleanup**
1. - [ ] **Miscellaneous Tasks**
1. - [ ] **Real-time Notifications for New Attendees**

...
