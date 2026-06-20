# Alumni Management Platform - Screen Inventory

## 1. Authentication Module

### 1.1 Login Screen

Purpose:
Allow users to log in using email/password or OTP.

Elements:

* Email field
* Password field
* Login button
* Forgot password link

---

### 1.2 Forgot Password Screen

Purpose:
Reset password via email OTP.

Elements:

* Email input
* Send OTP button
* OTP input
* Reset password field

---

## 2. Dashboard Module

### 2.1 Admin Dashboard

Purpose:
High-level analytics overview.

Widgets:

* Total Alumni Count
* Active Alumni
* Incomplete Profiles
* Pending Approvals
* Alumni by Location (chart)
* Alumni by Industry (chart)

---

## 3. Alumni Management Module

### 3.1 Alumni List Screen

Purpose:
View and filter all alumni.

Elements:

* Search bar
* Filters (batch, location, company, status)
* Table view
* Pagination

---

### 3.2 Alumni Detail Screen

Purpose:
View full alumni profile.

Sections:

* Personal Information
* Academic Information
* Professional Information
* Location Information
* Activity History

---

### 3.3 Create Alumni Screen

Purpose:
Add new alumni record manually.

Fields:

* Name
* Email
* Phone
* Batch
* Degree
* Company
* Location

---

### 3.4 Edit Alumni Screen

Purpose:
Modify alumni details (admin only).

Same as Create Alumni screen with prefilled data.

---

## 4. Bulk Upload Module

### 4.1 Upload Screen

Purpose:
Upload Excel/CSV file.

Elements:

* File upload button
* Download template link
* Upload button

---

### 4.2 Validation Results Screen

Purpose:
Show errors before import.

Elements:

* Error table
* Row-level validation messages
* Fix instructions
* Confirm import button

---

### 4.3 Upload History Screen

Purpose:
Track previous uploads.

Elements:

* File name
* Uploaded by
* Status
* Timestamp

---

## 5. Approval Module

### 5.1 Pending Approvals Screen

Purpose:
List all profile change requests.

Elements:

* Request list
* Filter by status
* Approve / Reject buttons

---

### 5.2 Approval Detail Screen

Purpose:
Compare old vs new data.

Elements:

* Side-by-side comparison
* Approve button
* Reject button
* Comments section

---

## 6. Reports Module

### 6.1 Location Report Screen

* Map view or chart
* Country/state breakdown

### 6.2 Industry Report Screen

* Pie chart / bar chart

### 6.3 Batch Report Screen

* Year-wise distribution

---

## 7. Administration Module

### 7.1 User Management Screen

* List users
* Assign roles
* Activate/deactivate users

---

### 7.2 Role Management Screen

* Define roles
* Assign permissions

---

### 7.3 Audit Trail Screen

* Activity logs
* Filter by user/action/date

---

## 8. Profile Module

### 8.1 My Profile Screen

* View personal info
* Edit request button

### 8.2 Change Password Screen

* Old password
* New password
* Confirm password