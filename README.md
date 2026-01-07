#  AutoWorx Barnyard Workshop Management System 
## Central Documentation Hub

Welcome to the central repository for the AutoWorx Barnyard Workshop Management System. This system is designed to streamline automotive services through a integrated mobile and web ecosystem.

---

##  1. Deliverables & System Overview
This section covers the high-level architecture and the scope of the project.

* **System Architecture**: Based on a client-server model using a RESTful API.
* **Core Components**:
    * **Frontend**: Flutter Mobile Apps and React Web App.
    * **Backend**: Django REST Framework (DRF).
    * **Database**: PostgreSQL for relational data storage.
* **Key Features**: Includes Appointment Management, Service Tracking, and Invoice Generation.

---

##  2. Developer Guide
Detailed technical specifications for maintaining and extending the codebase.

* **API Documentation**: 13 key endpoints including `/api/users/`, `/api/tasks/`, and `/api/invoices/`.
* **Database Schema**: Overview of models such as `User`, `Car`, `Service`, and `TaskReport`.
* **Business Logic**: Implementation details for real-time service status updates (Inspection, In Progress, Completed).
* **Modular Design**: The system is built to be easily modified or extended.

---

##  3. Installation & Setup Guide
Step-by-step instructions to get the environment running locally or in production.

* [**Containerization**: Use **Docker** to deploy the backend, frontend, and database components seamlessly.
* **Prerequisites**: 
    * Flutter SDK (for Mobile).
    * Node.js/npm (for React Web).
    * Python/Django (for Backend).
    * PostgreSQL (for Database).
* **Environment Configuration**: Ensure API endpoints and database credentials are set in the `.env` files.

---

##  4. User Guide
Instructions tailored to the three primary user roles within the system.

### **Customer Mobile App**
* How to register and manage your profile.
* Scheduling service appointments and selecting dates/times.
* Real-time tracking of vehicle service progress.
* Viewing and paying invoices.

### **Mechanic Mobile App**
* Logging in to view assigned tasks.
* Updating task reports with comments and status.
* Tracking parts used for each service.

### **Manager Web App**
* Administrative access for workshop oversight.
* Adding and managing new mechanic accounts.
* Managing the status of all upcoming appointments.
* Generating comprehensive service reports and invoices.

---

##  5. Security Standards
* **Access Control**: Role-Based Access Control (RBAC) ensures users only access data relevant to their role.
* **Data Protection**: Sensitive data, including passwords and payment details, is encrypted.
* **Authentication**: All passwords are hashed and stored securely.
