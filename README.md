# 🌱 FarmBridge: Bridging Farmers & Consumers

<div class="header-banner" style="background: linear-gradient(135deg, #38b2ac, #319795); padding: 2rem; border-radius: 12px; color: white; margin-bottom: 2rem;">
  <h1 style="margin: 0; font-size: 2.5rem;">FarmBridge</h1>
  <p style="margin: 0.5rem 0 0; font-size: 1.2rem;">Direct farm-to-consumer marketplace platform</p>
</div>

**FarmBridge** is a full-stack web application developed during a hackathon to bridge the gap between farmers and consumers. It enables farmers to showcase their produce, connect with buyers, and build trust — all in one platform.

🏆 **Winner of the Full Stack Web Development Hackathon** at the University of South Asia — built by Team Terminator

---

## 💡 Challenge

**Build a full-stack web application that connects farmers and consumers.**

We responded with **FarmBridge** — a modern, scalable agri-tech solution empowering both farmers and consumers.

<div class="highlight-box" style="background-color: #f0fff4; border-left: 4px solid #48bb78; padding: 1rem; margin: 1.5rem 0; border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; color: #2f855a;">❗ The Problem</h3>
  <p>Farmers in many regions face major hurdles:</p>
  <ul style="margin-bottom: 0;">
    <li>❌ Limited or no digital presence</li>
    <li>❌ Dependence on middlemen who reduce their profit margins</li>
    <li>❌ Lack of direct connection and trust with consumers</li>
    <li>❌ No centralized online platform to market their goods</li>
  </ul>
</div>

<div class="solution-box" style="background-color: #ebf8ff; border-left: 4px solid #4299e1; padding: 1rem; margin: 1.5rem 0; border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; color: #2b6cb0;">✅ Our Developed Solution</h3>
  <p><strong>FarmBridge</strong> directly addresses these issues by offering:</p>
  <ul style="margin-bottom: 0;">
    <li>🌾 <strong>Farmer Profiles</strong> — Showcase farm products, locations, and background</li>
    <li>🛒 <strong>Consumer Dashboard</strong> — Browse goods by category, farm</li>
    <li>📬 <strong>Messaging System</strong> — Enables real-time communication</li>
    <li>📦 <strong>Order Requests</strong> — Simple, secure order placement</li>
    <li>⚙️ <strong>Admin Panel</strong> — Manage users, listings, categories</li>
    <li>📈 <strong>Trust Building</strong> — Transparent digital marketplace</li>
  </ul>
</div>

---

## 🛠 Technologies Used

<div class="tech-grid" style="display: grid; grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); gap: 1rem; margin: 1.5rem 0;">
  <div class="tech-card" style="background: white; padding: 1rem; border-radius: 8px; text-align: center; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    <strong>Frontend</strong><br>React JS, Tailwind CSS
  </div>
  <div class="tech-card" style="background: white; padding: 1rem; border-radius: 8px; text-align: center; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    <strong>Backend</strong><br>Node JS, Express JS
  </div>
  <div class="tech-card" style="background: white; padding: 1rem; border-radius: 8px; text-align: center; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    <strong>Database</strong><br>MongoDB
  </div>
  <div class="tech-card" style="background: white; padding: 1rem; border-radius: 8px; text-align: center; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    <strong>Security</strong><br>JWT
  </div>
  <div class="tech-card" style="background: white; padding: 1rem; border-radius: 8px; text-align: center; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
    <strong>Hosting</strong><br>Vercel
  </div>
</div>

---

## 🧩 Features Overview

<div class="features-table" style="overflow-x: auto; margin: 1.5rem 0;">
  <table style="width: 100%; border-collapse: collapse;">
    <thead style="background-color: #f7fafc; border-bottom: 2px solid #e2e8f0;">
      <tr>
        <th style="padding: 12px; text-align: left;">Role</th>
        <th style="padding: 12px; text-align: left;">Features</th>
      </tr>
    </thead>
    <tbody>
      <tr style="border-bottom: 1px solid #e2e8f0;">
        <td style="padding: 12px;">👨‍🌾 Farmer</td>
        <td style="padding: 12px;">Register, login, create profile, list products, manage products, view & reply to messages</td>
      </tr>
      <tr style="border-bottom: 1px solid #e2e8f0;">
        <td style="padding: 12px;">🛒 Consumer</td>
        <td style="padding: 12px;">Browse listings, search by category, message farmers, request orders</td>
      </tr>
      <tr style="border-bottom: 1px solid #e2e8f0;">
        <td style="padding: 12px;">🛠️ Admin</td>
        <td style="padding: 12px;">Manage users, products, order requests, and categories via dashboard</td>
      </tr>
      <tr>
        <td style="padding: 12px;">🔐 Auth</td>
        <td style="padding: 12px;">Role-based access control</td>
      </tr>
    </tbody>
  </table>
</div>

---

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed
- VS Code or any other code editor
- Git (optional, for cloning the repository)

### File Structures

```plaintext
client/
├── public/
│   └── logo.png                       # Logo file
├── src/
│   ├── assets/                        # Images and other assets
│   ├── components/                    # Reusable UI components
│   ├── pages/                         # Pages
│   ├── redux/                         # State management
│   ├── App.jsx                        # React Router setup
│   └── main.jsx                       # Application entry point
├── .env                               # Environment variables
└── index.html                         # Root HTML file


api/
├── controllers/                       # Core logic
├── db/                                # Database connection
├── models/                            # Data schemas
├── routes/                            # API routes
├── utils/                             # Helper functions
├── .env                               # Environment variables
└── index.js                           # Main server file

Setup Instructions
Clone the Repository

bash
git clone https://github.com/yourusername/FarmBridge.git
Unzip the File

Open with VS Code

Open the project directory with VS Code or your preferred code editor.

Install Dependencies

Frontend:

bash
cd client
Create .env file:

env
VITE_BACKEND_URL = your_backend_url (http://localhost:5000)
Install dependencies:

bash
npm install
Run development server:

bash
npm run dev
Backend:

bash
cd api
Create .env file:

env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE =your_jwt_expiry (90d)
Install dependencies:

bash
npm install
Start server:

bash
npm run dev
Access the Application

Frontend: http://localhost:5173

Ensure proper communication between frontend and backend

🔗 Live Links
<div class="live-links" style="display: flex; gap: 1rem; margin: 1.5rem 0;"> <a href="https://FarmBridge.vercel.app" style="display: inline-block; background-color: #38a169; color: white; padding: 0.75rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: bold;">🌐 Live Web</a> <a href="https://github.com/ahadalireach/FarmBridge" style="display: inline-block; background-color: #2d3748; color: white; padding: 0.75rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: bold;">⭐ GitHub Repo</a> </div> ```