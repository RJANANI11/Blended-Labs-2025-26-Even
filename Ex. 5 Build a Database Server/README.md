# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: JANANI R
* **Register Number**: 212224040126
* **Date of Submission**: 19-03-26

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)
1.Launch an Amazon RDS DB instance with high availability.

2.Configure the DB instance to permit connections from your web server.

3.Open a web application and interact with your database.


---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1917" height="1024" alt="Screenshot 2026-03-19 154034" src="https://github.com/user-attachments/assets/00f49b24-5646-4e10-93c3-73cc7c5e9e17" />


---

### Screenshot 2: Database Service Running

<img width="1908" height="1033" alt="Screenshot 2026-03-19 160825" src="https://github.com/user-attachments/assets/17123b2d-068f-4e7d-8ce3-4f66bea48b11" />


---

### Screenshot 3: Sample Database and Table

<img width="1915" height="947" alt="Screenshot 2026-03-19 161211" src="https://github.com/user-attachments/assets/1c82c9d6-3b06-4a88-80ed-fff69e706be6" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
