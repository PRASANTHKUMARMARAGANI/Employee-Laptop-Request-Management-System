# 💻 Employee Laptop Request Management System

## 📌 Project Overview

The **Employee Laptop Request Management System** is a ServiceNow-based application designed to simplify and automate the process of requesting, reviewing, and approving laptops within an organization.

Employees can submit laptop requests through a request form, while IT Managers can review requests, approve or reject them, and manage their status. The system improves transparency, reduces manual work, and provides an organized request management process.

## 🎯 Objectives

- Simplify the employee laptop request process.
- Automate the approval workflow.
- Provide role-based access control.
- Allow IT Managers to manage laptop requests efficiently.
- Maintain request records in a centralized system.
- Prevent duplicate laptop requests within a specified period.

## ✨ Key Features

### 👨‍💻 Employee Module
- Submit new laptop requests.
- Provide request details and reasons.
- View submitted requests.
- Track request status.
- Access only authorized request information.

### 🧑‍💼 IT Manager Module
- View and manage employee laptop requests.
- Approve or reject requests.
- Update request statuses.
- Review employee request details.
- Manage the approval process.

### 🔐 Security & Access Control
- Role-based access control.
- Custom employee and IT Manager roles.
- Access Control Lists (ACLs).
- Employees can manage their own requests.
- Status updates are restricted to authorized managers.

### ⚙️ Workflow Automation
- Automated approval routing using Flow Designer.
- Manager approval and rejection process.
- Request status management.
- Notifications for request updates.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| ServiceNow | Application development platform |
| Service Catalog | Employee request submission |
| Record Producer | Custom laptop request form |
| Flow Designer | Workflow and approval automation |
| Business Rules | Server-side business logic |
| Access Control Lists (ACLs) | Security and permissions |
| Custom Tables | Store laptop request records |

## 🏗️ System Architecture

```text
       Employee
           |
           v
   Laptop Request Form
       (Record Producer)
           |
           v
    Custom Request Table
           |
           v
      Flow Designer
           |
           v
     IT Manager Review
           |
      +----+----+
      |         |
      v         v
   Approved   Rejected
      |         |
      +----+----+
           |
           v
    Status Update
           |
           v
   Employee Notification
```

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| Employee | Create and view own laptop requests |
| IT Manager | Review, approve, reject, and manage requests |
| Administrator | Configure and maintain the application |

## 🔄 Application Workflow

1. Employee opens the laptop request form.
2. Employee enters the required details and submits the request.
3. The request is stored in the custom request table.
4. Flow Designer initiates the approval process.
5. IT Manager reviews the request.
6. Manager approves or rejects the request.
7. Request status is updated.
8. Employee receives the corresponding notification.

## 🧪 Testing

The application includes testing scenarios for:

- Laptop request submission.
- Request data validation.
- Role-based access permissions.
- Manager approval and rejection.
- Request status updates.
- Workflow execution.
- Duplicate request prevention.

## 🚀 Installation & Setup

1. Log in to your ServiceNow instance with administrator access.
2. Open the application development environment.
3. Create or access the Employee Laptop Request Management application.
4. Configure the custom request table and required fields.
5. Configure the Record Producer.
6. Set up Business Rules and Flow Designer workflows.
7. Configure employee and IT Manager roles.
8. Create the required ACL rules.
9. Test the complete request and approval workflow.

**Note:** The application must be configured and tested in a compatible ServiceNow instance before production deployment.

## 📂 Project Documentation

The repository includes documentation covering the following phases:

1. Ideation Phase
2. Requirement Analysis
3. Project Design Phase
4. Project Planning Phase
5. Project Development Phase
6. Project Testing Phase
7. Project Documentation

## 🔮 Future Enhancements

- Dashboard for tracking laptop requests.
- Advanced reporting and analytics.
- Email and mobile notifications.
- Integration with IT asset management.
- Automated laptop availability checking.
- Enhanced approval escalation mechanisms.

## 👨‍💻 Developer

**M. Prasanth Kumar**

- GitHub: [PRASANTHKUMARMARAGANI](https://github.com/PRASANTHKUMARMARAGANI)
- Project: Employee Laptop Request Management System

## 📄 License

This project is developed for educational and academic purposes.

---

⭐ If you find this project useful, consider giving the repository a star!
