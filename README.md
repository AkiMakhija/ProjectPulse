# ProjectPulse 📊

A full-stack project management system built with Spring Boot and React, featuring comprehensive project tracking, team collaboration, and subscription-based access control.

## ✨ Key Features

- **Project Management** - Create, organize, and track projects with intuitive dashboards
- **Team Collaboration** - User invitation system with role-based access control
- **Issue Tracking** - Comprehensive issue management with status tracking and assignments
- **Real-time Comments** - Collaborative feedback system for seamless team communication
- **Subscription Plans** - Tiered access control with integrated payment processing
- **Advanced Search** - Powerful filtering and search capabilities across projects and issues
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
