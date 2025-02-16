
# YouCode Event Management Platform

## Table of Contents
1. [Project Overview](#project-overview)
2. [Architecture](#architecture)
3. [Key Features](#key-features)
4. [User Roles](#user-roles)
5. [Functional Requirements](#functional-requirements)
6. [Non-Functional Requirements](#non-functional-requirements)
7. [Getting Started](#getting-started)
8. [Contributing](#contributing)
9. [License](#license)

## Project Overview

The YouCode Event Management Platform is a comprehensive solution designed to optimize the management and distribution of events, courses, and multimedia content for YouCode. This platform aims to provide an engaging and personalized user experience while addressing the specific needs of various stakeholders, including students (both admitted and non-admitted to SAS), professors, cameramen, and administration.

### Problem Statement

YouCode faces the challenge of efficiently managing an increasing volume of events, videos, and courses while ensuring that each user group can quickly and easily access relevant content. This situation leads to several issues, including information overload, navigation difficulties, lack of personalization, complex administration, limited user engagement, and challenges in content impact assessment for creators.

## Architecture

The YouCode platform is built on a clear organizational structure that defines the roles and interactions of different actors within the system.

## Key Features

1. Event Management
2. User Authentication and Authorization
3. Content Creation and Submission
4. Content Validation and Publishing
5. Personalized User Experiences
6. Real-time Communication
7. Analytics and Reporting
8. Video Streaming Capabilities

## User Roles

1. Administration
2. Cameraman
3. Professors
4. Students (Admitted to SAS)
5. Students (Non-admitted to SAS)
6. BDE (Bureau des Étudiants)
7. CME (Comité des Membres Étudiants)
8. Coach

## Functional Requirements

### Administration
- Dashboard with detailed platform statistics
- User management (create, modify, delete accounts)
- Event validation and publishing
- Urgent message system to cameramen and professors
- Video streaming capabilities

### Cameraman
- Event creation and modification
- File upload (videos and images)
- Communication with administration
- Event search and management

### Professors
- Course creation and submission
- Course statistics viewing
- Profile management

### Students
- Event viewing and consultation
- Streaming capabilities (for SAS-admitted students)

## Non-Functional Requirements

### Security
1. Authentication and Authorization
   - Robust authentication system
   - Two-factor authentication (2FA) for critical accounts
   - Role-based access control

2. Protection Against Common Attacks
   - SQL injection prevention
   - Cross-Site Scripting (XSS) protection
   - Cross-Site Request Forgery (CSRF) protection
   - Brute force attack prevention

3. Data Security
   - HTTPS implementation
   - Secure password storage
   - Regular data backups

4. Monitoring and Audits
   - Activity logging
   - Regular security audits

5. Resilience
   - Disaster recovery plan
   - High availability (99.9% uptime)

## Getting Started

(Include instructions on how to set up and run the project locally)

## Contributing

(Include guidelines for contributing to the project)

## License

(Specify the license under which the project is released)
