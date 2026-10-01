# Script-Controlled ACL – Restrict Record Access Based on Field Value

## Project Overview

This project is a ServiceNow-based micro project that implements **Script-Controlled Access Control Lists (ACLs)** to restrict access to institution records based on user roles and branch values.

The project demonstrates record-level security by controlling **Read, Create, Write, and Delete** operations on the Institution Details table.

## Project Objective

The objective of this project is to implement record-level security in ServiceNow using Access Control Lists (ACLs) and script-based conditions.

The system allows different users to access records based on their assigned roles and branch conditions, while administrators have full access.

## Key Features

* Create test users and custom roles.
* Create the Institution Details table.
* Store branch information such as ECE, EEE and CSE.
* Configure Read ACL.
* Configure Create ACL.
* Configure Write ACL.
* Configure Delete ACL.
* Test access using user impersonation.
* Provide full access to administrators.

## Roles and Permissions

| Role    | Permission  |
| ------- | ----------- |
| `bb1`   | Read        |
| `bb2`   | Create      |
| `bb3`   | Write       |
| `bb4`   | Delete      |
| `admin` | Full Access |

## Institution Details Table

The project uses an **Institution Details** table to store institution-related records.

The main fields include:

* Student Roll Number
* Student Name
* Faculty Name
* Branch
* Email
* Phone Number
* Description

The Branch field contains:

* ECE
* EEE
* CSE

## Project Workflow

```text
Administrator
      ↓
User & Role Management
      ↓
Institution Details Table
      ↓
ACL Configuration
      ↓
Check User Role + Branch
      ↓
Allow / Deny Access
      ↓
Testing Using User Impersonation
```

## Project Phases

### Phase 1 – Brainstorming

Identify the problem and select the Script-Controlled ACL project.

### Phase 2 – Requirement Analysis

Identify the functional and non-functional requirements of the project.

### Phase 3 – Project Design

Design the proposed solution, main features and system architecture.

### Phase 4 – Project Planning

Plan the project stages, sprint schedule and project backlog.

### Phase 5 – Project Development

Implement the users, roles, Institution Details table and ACL configurations in ServiceNow.

### Phase 7 – Documentation

Prepare the final project documentation, screenshots and related project materials.

## Technologies Used

* ServiceNow
* ServiceNow Developer Instance
* Access Control Lists (ACL)
* JavaScript
* ServiceNow Database
* User and Role Administration

## Testing

The ACL functionality is tested using user impersonation.

The following operations are verified:

* Read
* Create
* Write
* Delete
* Administrator full access

## Project Status

**Status: In Progress**

The ServiceNow configuration and ACL functionality have been implemented. Project documentation is being prepared.

## Expected Outcome

The project demonstrates how Script-Controlled ACLs can be used to provide controlled access to Institution Details records in ServiceNow.

Unauthorized users are restricted from performing operations for which they do not have permission, while administrators retain full access.

## Project Structure

```text
ServiceNow-Script-Controlled-ACL/
│
├── README.md
│
├── Phase-1-Brainstorming/
│   └── Phase-1-Brainstorming.docx
│
├── Phase-2-Requirement-Analysis/
│   └── Phase-2-Requirement-Analysis.docx
│
├── Phase-3-Project-Design/
│   └── Phase-3-Project-Design.docx
│
├── Phase-4-Project-Planning/
│   └── Phase-4-Project-Planning.docx
│
├── Phase-5-Project-Development/
│   └── Phase-5-Project-Development.docx
│
└── Phase-7-Documentation/
    └── Phase-7-Documentation.docx
```
