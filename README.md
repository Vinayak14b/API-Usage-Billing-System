
## Overview

The **API Usage Billing System** is a comprehensive, modern platform for managing electricity billing processes. Built with **Spring Boot**, **JWT**, and **React.js**, the system provides a secure, scalable, and user-friendly solution. The platform automates bill generation, payment processing, and integrated with **Razorpay** for seamless online transactions.

### Key Features

- **Spring Boot Backend**: Manages business logic, handles JWT-based authentication, and provides REST API endpoints.
- **React.js Frontend**: Delivers a responsive and interactive user interface.
- **Razorpay Integration**: Facilitates secure online payments.
- **Bill Generation**: Automatically calculates and generates monthly electricity bills.
- **Receipt Generation**: Provides automatic receipt generation for completed payments.

---

## Development Lifecycle

The development of the API Usage Billing System was completed over a span of 16 days. Below is a detailed breakdown of the process:

- **Day 1-2: Planning & Design**
  - Defined project scope and requirements.
  - Created wireframes and UI mockups for the frontend.
  - Designed the database schema to manage user data, billing information, and payments.

- **Day 3-5: Backend Development**
  - Set up the Spring Boot project structure.
  - Implemented core business logic including user management, bill generation, and payment processing.
  - Integrated JWT for secure authentication.
  - Developed REST API endpoints for frontend communication.

- **Day 6-8: Frontend Development**
  - Set up the React.js project using Vite.
  - Developed key components for user registration, login, and bill viewing.
  - Integrated Razorpay for payment processing.
  - Styled the application using Tailwind CSS.

- **Day 9-11: Integration & Testing**
  - Integrated the frontend with backend APIs.
  - Conducted integration testing to ensure system stability.
  - Fixed bugs and optimized performance.

- **Day 12-14: Deployment Preparation**
  - Prepared the application for deployment, including environment configuration and packaging.
  - Configured the database and application server.
  - Wrote deployment scripts and documentation.

- **Day 15-16: Final Testing & Documentation**
  - Conducted final testing to ensure the system was production-ready.
  - Documented the project, including setup instructions, API documentation, and user guides.
  - Created this README and organized images for a clear overview of the project.

---

## Business Case

The API Usage Billing System addresses inefficiencies and complexities associated with manual billing processes. By automating bill generation and payment collection, the system reduces operational costs, minimizes errors, and enhances customer satisfaction. The integration with Razorpay ensures secure and convenient payment options, making it easier for users to pay their bills on time.

---

## How to Run

1. **Clone the Repository**:

   ```bash
   git clone  https://github.com/Vinayak14b/API-Usage-Billing-System.git

3. **Backend Setup**:
   - Navigate to the `eb-billing-system` directory.
   - Configure the `.env` file with your database credentials and other environment variables.
   - Build and run the Spring Boot application:
     \`\`\`bash
     mvn clean package
     java -jar target/eb-billing-system.jar
     \`\`\`

4. **Frontend Setup**:
   - Navigate to the `React-vite-frontend` directory.
   - Install dependencies and start the development server:
     \`\`\`bash
     npm install
     npm run dev
     \`\`\`

5. **Access the Application**:
   - Open your browser and go to `http://localhost:5173`.

---

## Technologies Used

- **Backend**: Spring Boot, Hibernate, JWT
- **Frontend**: React.js, Vite, Tailwind CSS
- **Payment Gateway**: Razorpay
- **Database**: MySQL

---

## Business Benefits

- **Reduced Operational Costs**: Automates repetitive tasks, saving time and resources.
- **Improved Accuracy**: Eliminates manual errors in billing.
- **Enhanced User Experience**: Simple and secure online payments.
- **Scalability**: Easily handles increasing numbers of users and transactions.

---


## 

---
