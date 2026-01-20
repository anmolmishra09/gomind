# WanderMind
WanderMind is an AI-powered trip planner using React, Gemini AI, Firebase, and TailwindCSS to create personalized travel itineraries effortlessly.

## Project Overview
**WanderMind** is an advanced full-stack AI-powered trip planner designed to streamline the travel planning process. By leveraging cutting-edge technologies such as **React, Gemini AI, TailwindCSS, and Firebase**, this platform enables users to generate personalized travel itineraries, authenticate securely using Google, and explore locations with comprehensive details sourced from Google APIs.

## 🚀 Features

- 🔐 Secure User Authentication (Login / Signup)
- 🧭 Personalized Travel Dashboard
- 📍 Explore Destinations & Travel Ideas
- 📱 Fully Responsive UI
- ⚡ Fast and Scalable Architecture

---

## 🛠️ Tech Stack

**Frontend**
- React.js / Next.js  
- Tailwind CSS  
- JavaScript (ES6+)

**Backend**
- Node.js  
- Express.js  
- REST APIs  

**Database**
- MongoDB / MySQL (configurable)

**Authentication**
- JWT (JSON Web Tokens)
- Password Encryption (bcrypt)

---

## 🔑 Login Flow

1. User registers with email & password  
2. Credentials are securely stored using encryption  
3. JWT token generated on successful login  
4. Protected routes accessible only to authenticated user


## Live Demonstration
🔗 **Check out WanderMind live:** [Live Application](https://wander-mind-eight.vercel.app/)

## Screenshots
_Add screenshots here to showcase the UI and functionality._

<p align="center">
  <img src="https://github.com/user-attachments/assets/246d9f71-9a83-4992-af60-6c2577aa7377" width="45%" />
  <img src="https://github.com/user-attachments/assets/2449a192-048e-45a5-a0ed-173f4621d7d2" width="45%" />

</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/997b7062-60df-430e-969e-a1a3d7804dc6" width="45%" />
  <img src="https://github.com/user-attachments/assets/b474c8fc-9be1-41ad-af02-ab02387a915b" width="45%" />
</p>

---

## 📂 Project Structure

WanderMind/
│
├── api/ # Backend utilities & services
│ ├── send-email.js # Email service
│ ├── package.json
│ └── package-lock.json
│
├── public/ # Static assets
│ ├── bg.jpg
│ ├── India-Gate.png
│ ├── Taj-Mahal.webp
│ └── icons & images
│
├── src/
│ ├── assets/ # Images & static resources
│ ├── components/ # Reusable UI components
│ ├── config/ # App configuration files
│ ├── constants/ # Constants & enums
│ ├── create-trip/ # Trip creation feature
│ ├── my-trips/ # User trips dashboard
│ ├── pages/ # Application pages
│ ├── services/ # API & service handlers
│ ├── view-trip/ # Trip detail views
│ ├── lib/ # Utility/helper functions
│ ├── index.css # Global styles
│ ├── main.jsx # App entry point
│ └── test/ # Testing files
│
├── index.html # Root HTML file
├── tailwind.config.js # Tailwind configuration
├── postcss.config.js # PostCSS configuration
├── vite.config.js # Vite configuration
├── eslint.config.js # ESLint rules
├── jsconfig.json # Path aliases
├── vercel.json # Deployment config
├── KILLER_FEATURES_IMPLEMENTATION.md
├── package.json
├── package-lock.json
└── README.md


---

## 🔐 Authentication Flow (Login)

1. User logs in using credentials
2. Frontend validates input
3. Secure session/token handling
4. Authenticated users can:
   - Create trips
   - View saved trips
   - Access protected routes

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/WanderMind.git

# Navigate into the project
cd WanderMind

# Install dependencies
npm install

# Run the frontend
npm run dev
For API utilities:

cd api
npm install
node send-email.js
🌐 Deployment
Frontend deployed using Vercel

Environment configs managed via vercel.json

🔮 Future Enhancements
🤖 AI-powered travel recommendations

🗺️ Interactive maps integration

👥 Social trip sharing

🔔 Notifications & reminders

🌐 Web3-based identity & rewards

🤝 Contributing
Contributions are welcome!
Fork the repository, create a new branch, and submit a pull request.

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Anmol Mishra
Aspiring Software Engineer | Frontend & Full Stack Developer
#
