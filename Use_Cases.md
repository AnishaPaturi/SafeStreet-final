# Use Cases for SafeStreet Project

## Actors
- **Citizen/User**: A person who uses the mobile app to report road damages.
- **Authority**: Government or municipal officials who manage and act on damage reports.
- **System**: The backend services including AI models and databases.
- **Chatbot**: AI-powered assistant for user queries.

## Use Cases

### 1. User Registration and Login
- **Actor**: Citizen/User
- **Description**: User registers with official and personal email, logs in with OTP verification.
- **Preconditions**: User has valid email addresses.
- **Postconditions**: User is authenticated and can access app features.

### 2. Upload Road Damage Image
- **Actor**: Citizen/User
- **Description**: User uploads an image of road damage via mobile app.
- **Preconditions**: User is logged in.
- **Postconditions**: Image is sent to backend for analysis.

### 3. Damage Classification
- **Actor**: System
- **Description**: AI model classifies the type and severity of damage from the uploaded image.
- **Preconditions**: Image is received by backend.
- **Postconditions**: Classification results are stored and linked to the report.

### 4. Generate Damage Report
- **Actor**: System
- **Description**: System generates a summary report based on AI analysis.
- **Preconditions**: Damage classification is complete.
- **Postconditions**: Report is available for viewing by user and authorities.

### 5. View Damage Reports
- **Actor**: Authority
- **Description**: Authority views all submitted damage reports via web dashboard.
- **Preconditions**: Authority is authenticated.
- **Postconditions**: Authority can filter, search, and review reports.

### 6. Update Report Status
- **Actor**: Authority
- **Description**: Authority updates the status of a damage report (e.g., Pending, In Progress, Resolved).
- **Preconditions**: Report exists in the system.
- **Postconditions**: Report status is updated and notifications sent.

### 7. Receive Notifications
- **Actor**: Citizen/User, Authority
- **Description**: Users receive email notifications about report status and OTPs.
- **Preconditions**: Relevant events occur (e.g., report update, login).
- **Postconditions**: Notification is sent successfully.

### 8. Chatbot Interaction
- **Actor**: Citizen/User
- **Description**: User interacts with chatbot for assistance and queries.
- **Preconditions**: Chatbot service is available.
- **Postconditions**: User receives relevant responses.

### 9. Password Reset
- **Actor**: Citizen/User
- **Description**: User requests OTP to reset password and updates it.
- **Preconditions**: User has registered email.
- **Postconditions**: Password is reset successfully.

### 10. System Maintenance
- **Actor**: System Administrator (optional)
- **Description**: Perform backups, updates, and monitor system health.
- **Preconditions**: System is operational.
- **Postconditions**: System remains stable and secure.
