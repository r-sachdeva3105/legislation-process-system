# Legislation Process Management System

A web-based system designed to simulate the legislative process in the **Federal Parliament of Canada**. This system manages the lifecycle of legislative bills from their creation, review, amendment, voting, and approval stages. Built using **PHP** with JSON/XML data storage and follows the **MVC pattern**.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Setup](#project-setup)
- [User Roles & Permissions](#user-roles--permissions)
- [System Workflow](#system-workflow)
- [UML Diagrams](#uml-diagrams)
- [Contribution Summary](#contribution-summary)

---

## Project Overview

This system is a simulation of the Canadian Federal Parliament's legislative process. It allows **Members of Parliament** to draft bills, submit them for review, and participate in voting. **Reviewers** can propose amendments to bills, and **Administrators** oversee the entire process, including managing users, starting voting sessions, and approving or rejecting bills.

### Learning Objectives

1. Develop a multi-tier architecture using **PHP** and follow the **MVC pattern**.
2. Implement a complex system adhering to **SOLID principles** and the **Repository pattern**.
3. Use JSON/XML files for state management and persistent data storage.
4. Collaborate effectively as a team to design and implement a real-world software solution.

---

## Features

- **Bill Creation**: MPs can draft and submit new bills for review.
- **Amendments**: Reviewers can propose changes to bills with suggested amendments.
- **Voting System**: MPs can cast votes on bills, and results are calculated.
- **Role-based Access Control**: Each user role (MP, Reviewer, Admin) has specific permissions.
- **Bill Tracking**: Versioning system to track changes in bill drafts.
- **Session & Cookie Management**: Secure user authentication with session and cookie handling.
- **Dashboard**: User-specific dashboards showing pending bills, voting sessions, and actions.

---

## Technologies Used

- **PHP**: Backend logic and business processes.
- **JSON/XML**: Data storage for bills, users, amendments, and votes.
- **HTML/CSS**: Frontend interface and user experience.
- **GitHub**: Version control and collaboration.
- **Graphviz**: UML diagrams (Class and Sequence diagrams).

---

## Project Setup

### Prerequisites

- **PHP**: Version 7.4 or higher
- **Web Server**: Apache or any PHP-capable web server
- **Git**: For version control
- **Graphviz**: For UML diagrams (optional)

### Steps to Run the Project Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/r-sachdeva3105/legislation-process-system.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd legislation-process-management-system
   ```
3. **Set up the PHP environment**:

   - Ensure PHP is installed on your system.
   - Set up your web server to serve files from the `/public` directory.

4. **Start the application**:

   - Access the application in the browser at `http://localhost`.

5. **User credentials**:
   - For testing, use the pre-created user accounts (MP, Reviewer, Admin) provided in the `users.json` file.

---

## User Roles & Permissions

| **Role**                      | **Permissions**                                                             |
| ----------------------------- | --------------------------------------------------------------------------- |
| **Member of Parliament (MP)** | Create, edit own bills, vote on bills, view voting results.                 |
| **Reviewer**                  | Suggest amendments, comment on bills, view bills and results.               |
| **Administrator**             | Manage users, initiate voting, approve/reject bills, access system reports. |

---

## System Workflow

1. **Bill Creation**: MPs draft and submit bills.
2. **Amendments**: Reviewers suggest changes.
3. **Voting**: MPs vote on bills.
4. **Approval**: Admins approve or reject bills based on votes.

---

## UML Diagrams

- **Class Diagram**: [Download UML Class Diagram](https://github.com/r-sachdeva3105/legislation-process-system/blob/main/docs/UMLClassDiagram.pdf)
- **Sequence Diagram**: [Download UML Sequence Diagram](https://github.com/r-sachdeva3105/legislation-process-system/blob/main/docs/UMLSequenceDiagram.pdf)

---

## Contribution Summary

Each group member contributed as follows:

- **Rajat**:
- **Shrabani**:
- **Abdun**:
- **Mitali**:
- **Pranav**:

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contact Information

For any queries or clarifications, feel free to contact any group member or visit our GitHub repository.
