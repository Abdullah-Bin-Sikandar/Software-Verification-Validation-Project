# Software Requirements Specification (SRS)
## Requirements – SRS Review Activity

---

## 1. Usability

### Original Requirement
The system should be user-friendly.

### Issues Identified
- Ambiguous  
- Not measurable  
- Not verifiable  
- Lacks specificity  

### Revised Requirement
The system shall enable a first-time user to complete the registration process within **3 minutes** without requiring external assistance.

---

## 2. Secure Storage of Student Records

### Original Requirement
The system shall store student records safely.

### Issues Identified
- Lacks specificity  
- Not measurable  
- Not verifiable  

### Revised Requirement
The system shall store all student records in a database encrypted using **AES-256 encryption**.

---

## 3. System Performance

### Original Requirement
The system should load quickly.

### Issues Identified
- Not measurable  
- Not specific  
- Not verifiable  

### Revised Requirement
The system shall load the dashboard page within **2 seconds** under normal operating conditions, supporting up to **100 concurrent users**.

---

## 4. User Account Management

### Original Requirement
The system shall allow users to register, log in, and manage their profile.

### Issues Identified
- Not atomic (multiple requirements combined into one)  
- Insufficient detail  

### Revised Requirements

**4.1 Registration**  
The system shall allow users to register using a valid email address and password.

**4.2 Login**  
The system shall authenticate registered users using valid login credentials.

**4.3 Profile Management**  
The system shall allow users to update their profile information, including their name and password.

---

## 5. Notifications

### Original Requirement
The system shall send notifications.

### Issues Identified
- Not specific  
- Not measurable  
- Incomplete  

### Revised Requirement
The system shall send an email notification to the user within **5 minutes** of successful registration.
