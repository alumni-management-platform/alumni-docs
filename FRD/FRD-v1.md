# Functional Requirements Document (FRD)

# Project

Alumni Management Platform

# Version

1.0

---

# Module 1 - Authentication

## FR-AUTH-001 Login

Description:
System shall allow registered users to authenticate using email and password.

Inputs:

* Email
* Password

Validations:

* Email mandatory
* Password mandatory
* Email format validation

Outputs:

* Successful login
* Error message

---

## FR-AUTH-002 Forgot Password

Description:
System shall allow users to reset password using OTP sent to registered email.

Inputs:

* Email
* OTP
* New Password

Validations:

* Registered email required
* OTP validation required

Outputs:

* Password reset success
* Error message

---

# Module 2 - Alumni Management

## FR-ALUMNI-001 Create Alumni

Description:
Administrator can create and maintain a complete alumni profile.

---

### Personal Information

* First Name
* Last Name
* Gender
* Date Of Birth
* Recent Photograph (Profile Image URL / Upload)

---

### Contact Information

* Primary Email
* Alternate Email (Optional)
* Primary Mobile Number (with Country Code)
* Alternate Mobile Number (with Country Code)
* Alternate Contact Person Name (for Alternate Number)

---

### Academic Information

* Roll Number (Unique Identifier)
* House
* Entry Batch Year
* Pass Out Batch Year
* Degree
* Branch

---

### Professional Information

* Current Employment Type
  Supported Values:

  * Job
  * Business
  * Agriculture
  * Self-Employed
  * Unemployed
  * Retired

* Current Company / Organization Name (or Business Name)

* Job Title / Role (if applicable)

* Sector (Mandatory)

  Supported Values:

  * IT / Software
  * Education
  * Healthcare
  * Agriculture
  * Government
  * Manufacturing
  * Finance
  * Retail
  * Other

---

### Permanent Location Information

* Permanent Address Line 1
* Permanent Address Line 2
* Permanent City
* Permanent District
* Permanent State
* Permanent Country
* Permanent Postal Code

---

### Current Location Information

* Current Address Line 1
* Current Address Line 2
* Current City
* Current District
* Current State
* Current Country
* Current Postal Code

---

### System Information

* Alumni Status

Supported Values:

* Active
* Inactive
* Deceased
* Unverified

---

### Validations

* First Name mandatory
* Primary Email mandatory
* Roll Number mandatory
* Entry Batch Year mandatory
* Pass Out Batch Year mandatory
* Primary Mobile Number mandatory
* Sector mandatory
* Alumni Status mandatory

---

## FR-ALUMNI-002 View Alumni

Description:
Authorized users can view alumni profile.

Displayed Sections:

* Personal Information
* Academic Information
* Professional Information
* Location Information
* Audit History

---

## FR-ALUMNI-003 Search Alumni

Description:
Users can search alumni using multiple filters across academic, professional, and location dimensions.

---

### Basic Search

* First Name
* Last Name
* Roll Number
* Primary Email
* Primary Mobile Number

---

### Academic Filters

* House
* Entry Batch Year
* Pass Out Batch Year
* Degree
* Branch

---

### Professional Filters

* Current Employment Type
* Current Company / Organization
* Sector

---

### Location Filters

* Permanent Country

* Permanent State

* Permanent District

* Permanent City

* Current Country

* Current State

* Current District

* Current City

---

### Status Filters

* Active
* Inactive
* Deceased
* Unverified

---

### Outputs

* Filtered Alumni List
* Sorting (Name, Batch, Company)
* Pagination
* Export (CSV/Excel)

---

## FR-ALUMNI-004 Edit Alumni

Description:
Authorized users can update alumni profile.

Workflow:

1. User submits change
2. Request enters approval queue
3. Administrator reviews
4. Approve or reject
5. Audit record created

---

## FR-ALUMNI-005 Alumni Status

System shall support:

* Active
* Inactive
* Deceased
* Unverified