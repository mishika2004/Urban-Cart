# 🛒 Urban Cart: AI-Powered E-Commerce Ecosystem

Urban Cart is a high-performance, full-stack e-commerce platform that redefines the digital shopping experience by integrating AI-driven personalization and automated customer assistance.

Built with a decoupled architecture, the system focuses on bridging the gap between standard retail and intelligent automation through real-time search-tracking agents and a sophisticated recommendation engine.

---

## 🏗️ System Architecture

Urban Cart is architected as a modern distributed system, separating concerns between a responsive user interface and a secure, logic-heavy backend.

- **Frontend:** A dynamic, state-driven React environment optimized for high-speed browsing and real-time UI updates.  
- **Backend:** A robust Node.js/Express server handling complex business logic, secure transactions, and AI orchestration.  
- **Database:** A flexible NoSQL layer (MongoDB) designed for high-concurrency product lookups and user session persistence.  

---

## 🧠 Intelligent Features

### 1. Context-Aware Chatbot Agents
Unlike static FAQ bots, the Urban Cart Assistant is a real-time agent that:

- **Monitors Search Intent:** Updates users dynamically based on the products they are currently exploring.  
- **Natural Language Discovery:** Allows users to find products through conversational queries rather than rigid filters.  
- **Proactive Engagement:** Recommends relevant catalog items during the conversation to reduce bounce rates.  

---

### 2. Personalized Recommendation Engine
The system utilizes a data-driven engine to analyze user behavior:

- **Behavioral Tracking:** Tracks product views and search history to build a local preference profile.  
- **Smart Suggestions:** Implements "Suggested for You" logic to increase Cross-Sell and Up-Sell opportunities.  

---

## 🛡️ Security & Authentication

Urban Cart prioritizes data integrity and user privacy using industry-standard protocols:

- **Credential Hashing:** Leverages bcrypt to ensure passwords are never stored in plain text, protecting against rainbow table attacks.  
- **Stateless Session Management:** Implements jsonwebtoken (JWT) for secure, scalable authentication across API endpoints.  
- **Secure Cookie Handling:** Utilizes cookie-parser to manage signed, secure cookies for session persistence and protection against CSRF vulnerabilities.  

---

## 🚀 Key Results

- **Enhanced Discovery:** Reduced search time by providing direct AI-assisted product links via the chatbot.  
- **High Performance:** Optimized API response times through efficient database indexing and middleware filtering.  
- **Zero-Trust Auth:** Achieved 100% secure route protection using JWT-based middleware guards.  

---

## 🛠️ Tech Stack

### Core Packages
- **bcrypt** – Secure password hashing and encryption  
- **jsonwebtoken** – Token-based authentication and secure API access  
- **cookie-parser** – Parsing and securing browser cookies  

### Development Environment
- **Environment:** Node.js (v18+)  
- **Frontend:** React.js / Tailwind CSS  
- **Backend:** Express.js  
- **Database:** MongoDB  

---

## 📂 Project Structure

```
Urban_Cart/
 ├── Backend/      # Node.js/Express Server & API Logic
 ├── Frontend/     # React.js UI & State Management
 ├── models/       # Database Schemas (Users, Products, Orders)
 ├── routes/       # Protected API Endpoints
 ├── middleware/   # JWT Auth & Security Filters
 ├── ai_engine/    # Chatbot Logic & Recommendation Algorithms
 └── README.md     # Project Documentation
```

---

## ⚙️ Installation

### 1. Clone the repository
```
git clone https://github.com/yourusername/urban-cart.git
```

### 2. Install Backend Dependencies
```
cd Major_Project/Backend
npm install
```

### 3. Install Frontend Dependencies
```
cd ../Frontend
npm install
```

### 4. Environment Setup
Create a `.env` file in the Backend directory and add your `MONGO_URI` and `JWT_SECRET`.

---

## 📸 Screenshots

Add screenshots here

---

## 📈 Future Improvements

- Payment integration  
- Order tracking system  
- Admin dashboard  