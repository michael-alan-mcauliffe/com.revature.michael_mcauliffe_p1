# Tuition Reinbursement Management System
## Overview
The Tuition Reinbursement Management System (TRMS) is an application to help employers manage reimbursement requests from employees from tuition expenses.

## Technologies Used
- Java 8
- Gradle
- JDBC
- JavaScript
- Jenkins
- Postgres

## Features
Currently Implemented Features:
- Login system for dynamically determining if user is a basic user or an admin.
- Employees can make reimbursement requests for various tuition related expenses (i.e. university courses, certifications, etc).
- System will dynamically list requests based on employee, that employee's administrative privilege, and the status of the request.

Upcoming Features:
- Allows approvers to send a messages to those involved in a request allowing them to ask for more information or clearification.
- System automatically determines the appropriate managers in the chain of command to request approval from.
- System will automatically any approver who does not approve a request in a timely manner.
- System will show the amount an employee has left in thier expense account based on prior approved requests and current pending requests. This is reset on subsequest new years.

## Getting Started
- Clone the repository
  - `gh repo clone mcawful/com.revature.michael_mcauliffe_p1` 
