# SafeRoute AI – Smart Insurance for Delivery Workers

## Table of Contents

1. [Overview](#overview)  
2. [Problem Statement](#problem-statement)  
3. [Target Persona](#target-persona)  
4. [Real-Life Scenario](#real-life-scenario)  
5. [Solution Overview](#solution-overview)  
6. [Workflow](#workflow)  
7. [Weekly Premium Model](#weekly-premium-model)  
8. [Parametric Triggers](#parametric-triggers)  
9. [AI/ML Integration](#aiml-integration)  
10. [Tech Stack](#tech-stack)  
11. [System Architecture](#system-architecture)  
12. [Data Flow and Processing](#data-flow-and-processing)  
13. [Security and Fraud Detection](#security-and-fraud-detection)  
14. [Performance and Scalability](#performance-and-scalability)  
15. [Features](#features)  
16. [Future Scope](#future-scope)  
17. [Installation and Setup](#installation-and-setup)  
18. [Testing](#testing)  
19. [Deployment](#deployment)  
20. [Contributing](#contributing)  
21. [License](#license)  
22. [Conclusion](#conclusion)  

---

## 1. Overview

SafeRoute AI is an AI-powered parametric insurance platform designed for delivery workers such as Swiggy and Zomato partners. It helps protect them from income loss caused by external disruptions like heavy rain, high pollution, and city restrictions.

The system uses environmental data and simple AI-based logic to assess risk, calculate weekly premiums, and automatically trigger payouts when conditions affect the worker’s ability to earn.

---

## 2. Problem Statement

Delivery workers often face unpredictable income loss due to factors such as:

- Heavy rainfall  
- High pollution levels  
- Curfews or local restrictions  

These conditions reduce working hours and directly impact their earnings. Currently, there is no automated system that compensates workers for such external disruptions.

---

## 3. Target Persona

- Delivery workers (Swiggy, Zomato, etc.)  
- Age group: 20–45  
- Daily income range: ₹300–₹800  
- Operating in urban and semi-urban areas  

They require a simple, reliable, and fast solution to protect their weekly income.

---

## 4. Real-Life Scenario

A delivery worker earns around ₹500 per day.

Due to heavy rainfall (greater than 20mm), the worker cannot work for the entire day. This results in a complete loss of income for that day.

SafeRoute AI detects the weather condition and automatically triggers a payout to compensate a portion of the lost earnings.

---

## 5. Solution Overview

SafeRoute AI provides a parametric insurance system that:

- Uses environmental data to evaluate risk  
- Calculates weekly premiums based on risk level  
- Monitors real-time conditions  
- Automatically triggers claims  
- Simulates instant payout for income loss  

---

## 6. Workflow

1. Worker registers with location details  
2. System collects environmental data (weather, AQI)  
3. AI logic evaluates risk level  
4. Weekly premium is calculated  
5. System continuously monitors trigger conditions  
6. When a trigger is detected, a claim is automatically initiated  
7. Compensation is provided to the worker  

---

## 7. Weekly Premium Model

| Risk Level | Premium | Coverage |
|------------|--------|----------|
| Low Risk   | ₹20/week | ₹200/day |
| Medium Risk| ₹30/week | ₹300/day |
| High Risk  | ₹40/week | ₹400/day |

Premiums are determined based on environmental risk conditions in the worker’s location.

---

## 8. Parametric Triggers

Claims are triggered automatically when specific conditions are met:

- Rainfall greater than 20mm  
- AQI greater than 300  
- Flood alerts  
- Government-imposed restrictions or curfews  

These triggers are based on reliable external data sources.

---

## 9. AI/ML Integration

The system uses basic AI logic to:

- Predict risk using weather and pollution data  
- Adjust weekly premiums dynamically  
- Detect simple fraud cases such as:
  - Duplicate claims  
  - Location mismatch  

---

## 10. Tech Stack

- Frontend: React  
- Backend: Node.js (planned)  
- Database: MongoDB (planned)  
- AI Module: Python  
- APIs: Weather API, AQI API  
- Deployment: Vercel (Frontend), Render or Vercel (Backend)  

---

## 11. System Architecture

User → Frontend → Backend → AI Logic → Trigger System → Claim Processing → Payout

---

## 12. Data Flow and Processing

1. Environmental data is collected from APIs  
2. Data is processed in the backend  
3. AI logic evaluates risk  
4. Trigger conditions are checked  
5. Claims are automatically processed when conditions are met  

---

## 13. Security and Fraud Detection

- Duplicate claim prevention  
- Basic location validation  
- Secure data handling practices  

---

## 14. Performance and Scalability

The system is designed to:

- Handle multiple users efficiently  
- Scale using cloud platforms  
- Process data in near real-time  

---

## 15. Features

- Dynamic weekly premium calculation  
- Automatic claim triggering  
- Real-time risk evaluation  
- Simple and user-friendly interface  

---

## 16. Future Scope

- Integration with real-time government APIs  
- Advanced fraud detection mechanisms  
- Integration with payment systems (UPI, Razorpay)  
- Mobile application development  
- Expansion to other gig worker platforms  

---

## 17. Installation and Setup

1. Clone the repository  
2. Install dependencies:
   npm install  
3. Start the application:
   npm start  

---

## 18. Testing

- Basic functional testing  
- Manual testing of trigger conditions  
- UI validation  

---

## 19. Deployment

- Frontend: Vercel  
- Backend: Render or Vercel  
- Simple deployment without CI/CD pipelines  

---

## 20. Contributing

1. Fork the repository  
2. Create a new branch  
3. Submit a pull request  

---

## 21. License

This project is available under the MIT License.

---

## 22. Conclusion

SafeRoute AI provides a practical solution to protect delivery workers from income loss caused by external disruptions. By combining AI-based risk evaluation with parametric insurance, the system enables automatic and timely compensation.

This approach improves financial stability for gig workers and demonstrates how technology can be used to solve real-world challenges.