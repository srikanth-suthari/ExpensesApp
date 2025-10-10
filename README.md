# ExpensesApp

# Project Title: 3-Tier Web Architecture.

A web application designed to help users easily track and manage their personal expenses.

---

## 🏛️ Architecture Overview

A detailed explanation of My 3-tier architecture. Describing how the Nginx web server (Presentation Tier), Node.js backend (Logic Tier), and MySQL database (Data Tier) interact with each other and which AWS services I used (e.g., EC2 for servers, MySQL in an EC2 instance for the database, VPC for networking).

**
![3-tier-architecture](https://github.com/user-attachments/assets/27f89e6f-6ab3-47e7-bdf0-363d68564ac1)
**

---
## 🛠️ Tech Stack

* **Web Server**: Nginx
* **Backend**: Node.js
* **Database**: MySQL
* **Cloud Provider**: AWS
* **Compute**: 3 Amazon EC2 Instances
* **Networking**: Amazon VPC, Security Groups

---
## 🚀 Getting Started

### Prerequisites

List of requirements for the project.
* Node.js (v18.x or higher)
* MySQL
* An AWS account

## ☁️ Deployment

The steps I took to deploy this application on AWS.

1.  **VPC Setup**: Configured the Virtual Private Cloud.
2.  **Database Tier**: Launched and configured the MysSQL Database and its security group.
3.  **Backend Tier**: Launched the EC2 instance for the Node.js app, installed dependencies, and configured environment variables to connect to the database.
4.  **Web Server Tier**: Launched the Nginx EC2 instance and configured it as a reverse proxy to point to the Node.js server.
