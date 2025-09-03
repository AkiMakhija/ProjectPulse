# ProjectPulse 📊

A full-stack project management system built with Spring Boot and React, featuring comprehensive project tracking, team collaboration, and subscription-based access control.

## ✨ Key Features

- **Project Management** - Create, organize, and track projects with intuitive dashboards
  <img width="679" height="425" alt="Screenshot 2025-09-03 at 10 54 25 AM" src="https://github.com/user-attachments/assets/a64a110b-2d45-4518-bb3a-302031c3c6bb" />

  <img width="1308" height="683" alt="Screenshot 2025-09-03 at 10 53 32 AM" src="https://github.com/user-attachments/assets/7c08fc95-57a8-4231-a180-68c8fccca986" />

- **Team Collaboration** - User invitation system with role-based access control
   <img width="1311" height="649" alt="Screenshot 2025-09-03 at 10 55 08 AM" src="https://github.com/user-attachments/assets/559ac41a-623b-4c0e-9486-1b512818dd24" />


- **Issue Tracking** - Comprehensive issue management with status tracking and assignments
  <img width="954" height="404" alt="Screenshot 2025-09-03 at 10 56 48 AM" src="https://github.com/user-attachments/assets/90b56cfa-e178-459a-a692-92941211219d" />

- **Real-time Comments** - Collaborative feedback system for seamless team communication
  
- <img width="311" height="578" alt="Screenshot 2025-09-03 at 11 03 49 AM" src="https://github.com/user-attachments/assets/26cb35ed-f23c-4055-8e61-327d5bd208e0" />

- **Subscription Plans** - Tiered access control with integrated payment processing
- **Advanced Search** - Powerful filtering and search capabilities across projects and issues
  <img width="1131" height="316" alt="Screenshot 2025-09-03 at 11 03 24 AM" src="https://github.com/user-attachments/assets/9cddb081-3bff-47f7-a51f-5575b623bbe0" />

  <img width="1131" height="296" alt="Screenshot 2025-09-03 at 11 02 37 AM" src="https://github.com/user-attachments/assets/84c70f91-ebb1-45e1-9078-32fb5b027d94" />

  <img width="1131" height="548" alt="Screenshot 2025-09-03 at 11 03 04 AM" src="https://github.com/user-attachments/assets/6614feb9-5753-4a2b-8deb-f826aeab72d0" />


- **Responsive Design** - Optimized for desktop, tablet, and mobile devices

## 🛠 Tech Stack

### Backend
- **Spring Boot** - RESTful API development
- **MySQL** - Database management and storage
- **Spring Security** - Authentication and authorization
- **JWT** - Secure token-based authentication
- **Spring Mail** - Email notifications and invitations
- **Razorpay** - Payment gateway integration

### Frontend
- **React** - Dynamic user interface
- **Redux** - State management
- **Tailwind CSS** - Modern styling framework
- **Shadcn UI** - Component library
- **React Router DOM** - Client-side routing

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Node.js 16+
- MySQL 8.0+
- Maven 3.6+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/projectpulse.git](https://github.com/AkiMakhija/ProjectPulse.git
   cd projectpulse
   ```

2. **Backend Setup**
   ```bash
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Database Configuration**
   - Create MySQL database: `projectpulse`
   - Update `application.properties` with your database credentials

## 📱 Features Overview

### Project Management
- Create and organize projects with custom categories
- Track project progress with visual indicators
- Set deadlines and milestones

### Issue Management
- Create, assign, and track issues
- Priority levels and status tracking
- Attachment support for detailed documentation

### Team Collaboration
- Invite team members via email
- Role-based permissions (Admin, Member, Viewer)
- Real-time comment system with notifications

### Subscription System
- Multiple pricing tiers
- Secure payment processing with Razorpay
- Feature access control based on subscription level

## 🔒 Security Features

- JWT-based authentication
- Spring Security integration
- Password encryption
- Protected API endpoints
- Input validation and sanitization

## 📄 API Documentation

The API follows RESTful conventions with endpoints for:
- Authentication (`/api/auth`)
- Projects (`/api/projects`)
- Issues (`/api/issues`)
- Users (`/api/users`)
- Subscriptions (`/api/subscriptions`)
