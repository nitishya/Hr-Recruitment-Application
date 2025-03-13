# HR Recruitment Application

## 📌 Overview
The **HR Recruitment Application** is a full-stack web application designed to streamline the hiring process. It enables recruiters to post job listings, candidates to apply for jobs, and admins to manage recruitment workflows efficiently.

## 🚀 Tech Stack
### 🔹 Backend:
- **Spring Boot (Microservices Architecture)**
- **MySQL** (Relational Database)
- **JWT Authentication**
- **Kafka (Messaging Service)**
- **Eureka Server (Service Discovery)**

### 🔹 Frontend:
- **Angular** (Modular UI Components)
- **RxJS (Reactive Programming)**
- **Bootstrap / Tailwind CSS**
- **WebSockets (Real-time Updates)**

## 🏗️ System Architecture
- **Backend:** Microservices communicating via API Gateway
- **Frontend:** Angular with modular architecture
- **Database:** MySQL (Transactional Data)
- **Messaging:** Kafka for event-driven workflows
- **Security:** JWT-based authentication

## 🔑 Features
### 🔹 Authentication & User Management
- User Registration & Login
- Role-based Access Control (Recruiters, Candidates, Admins)

### 🔹 Dashboard Module
- Personalized dashboard for each user type
- Job insights and application statistics

### 🔹 Job Module
- View and filter job listings
- Apply for jobs with resume & cover letter

### 🔹 Application Module
- Track job applications and status updates
- Admin/recruiters can review and shortlist candidates

### 🔹 Notification Module
- Real-time WebSocket-based notifications
- Email notifications for application updates

### 🔹 Profile Module
- Resume management
- Skills & Experience tracking

## 🔧 Setup Instructions
### 🔹 Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hr-recruitment-app.git
   ```
2. Navigate to the backend folder:
   ```bash
   cd backend
   ```
3. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
4. MySQL Configuration:
   - Update `application.properties` with your database credentials

### 🔹 Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   ng serve
   ```
4. Access the app at `http://localhost:4200`

## 📌 API Endpoints
### 🔹 Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Authenticate user & generate JWT

### 🔹 Jobs
- `GET /api/jobs` - Fetch all job listings
- `POST /api/jobs` - Create a new job (Recruiter only)
- `GET /api/jobs/{id}` - View job details

### 🔹 Applications
- `POST /api/applications` - Apply for a job
- `GET /api/applications/{userId}` - Fetch applications by user

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## 📬 Contact
For queries, reach out via:
- Email: your-email@example.com
- LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)
- GitHub: [Your Username](https://github.com/your-username)
