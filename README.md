
# 🎓 YouCode Event Management Platform

## 📚 Table of Contents
1. [Project Overview](#-project-overview)
2. [Architecture](#-architecture)
3. [Key Features](#-key-features)
4. [User Roles](#-user-roles)
5. [Functional Requirements](#-functional-requirements)
6. [Non-Functional Requirements](#-non-functional-requirements)
7. [Getting Started](#-getting-started)
8. [Contributing](#-contributing)
9. [License](#-license)

## 🌟 Project Overview

The YouCode Event Management Platform is a comprehensive solution designed to optimize the management and distribution of events, courses, and multimedia content for YouCode. This platform aims to provide an engaging and personalized user experience while addressing the specific needs of various stakeholders.

### 🎯 Problem Statement

YouCode faces the challenge of efficiently managing an increasing volume of events, videos, and courses while ensuring that each user group can quickly and easily access relevant content. This situation leads to several issues:

- 📊 Information overload
- 🧭 Navigation difficulties
- 👤 Lack of personalization
- 🔧 Complex administration
- 💡 Limited user engagement
- 📈 Challenges in content impact assessment for creators

## 🏗 Architecture

The YouCode platform is built on a clear organizational structure that defines the roles and interactions of different actors within the system.

```mermaid title="YouCode Platform Architecture" type="diagram"
graph TD
    A[Administration] -->|Manages| B[Users]
    A -->|Validates| C[Content]
    D[Cameraman] -->|Submits| E[Events]
    F[Professors] -->|Create| G[Courses]
    H[Students] -->|View| E
    H -->|Access| G
    I[BDE] -->|Organizes| J[Student Activities]
    K[CME] -->|Coordinates| L[Student Initiatives]
    M[Coach] -->|Guides| H