# 🤖 AI Mock Interview

[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Clerk](https://img.shields.io/badge/Clerk-5C4EE5?style=for-the-badge&logo=clerk&logoColor=white)](https://clerk.dev)
[![Gemini](https://img.shields.io/badge/Gemini-000000?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/gemini-api)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge&logo=shadcn-ui&logoColor=white)](https://ui.shadcn.com)
[![Recharts](https://img.shields.io/badge/Recharts-8884D8?style=for-the-badge&logo=recharts&logoColor=white)](https://recharts.org)

> 🚀 A cutting-edge AI-powered mock interview platform that helps candidates prepare for technical interviews with realistic practice sessions and detailed feedback.

---

## 📄 About

**AI Mock Interview** is a modern web application designed to help software engineering candidates prepare for technical interviews. Built with cutting-edge technologies, it provides an immersive interview experience with AI-generated questions, real-time speech-to-text recording, webcam integration, and comprehensive performance analytics.

The platform leverages Google Gemini AI to generate relevant, industry-standard interview questions and provide detailed, actionable feedback on candidate responses. With features like dark/light mode, mobile responsiveness, and PDF feedback generation, it offers a professional, user-friendly experience for interview preparation.

---

## ✨ Features

- 🎯 **AI-Generated Interview Questions**: Context-aware questions tailored to your tech stack and experience level
- 🎙️ **Speech-to-Text Answer Recording**: Real-time transcription of your verbal answers during interviews
- 📸 **Webcam Support**: Practice with video recording to improve non-verbal communication skills
- 📊 **AI Feedback with Ratings (1-10)**: Detailed evaluation across multiple dimensions (technical accuracy, communication, problem-solving)
- 📈 **Performance Insights Dashboard**: Visual analytics showing strengths and areas for improvement
- 🎯 **Overall Score Circular Chart**: Intuitive visualization of your overall performance score
- 💡 **Strong Areas vs Needs Improvement**: Clear breakdown of what you excel at and where to focus your efforts
- 🌗 **Dark/Light Mode Toggle**: Comfortable viewing in any lighting condition
- 📱 **Mobile Responsive Design**: Practice interviews on any device - desktop, tablet, or smartphone
- 📄 **PDF Download of Feedback**: Export your detailed feedback report as a professional PDF document
- 📚 **Interview History with Scores**: Track your progress over time with historical performance data
- 🏢 **About Us, Services, Contact Us Pages**: Professional information pages for visitors

---

## 🛠️ Tech Stack

### Core Technologies

| Category | Technologies |
|----------|--------------|
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000000?style=flat-square&logo=shadcn-ui&logoColor=white) |
| **Backend & APIs** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Clerk](https://img.shields.io/badge/Clerk-5C4EE5?style=flat-square&logo=clerk&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-000000?style=flat-square&logo=google&logoColor=white) |
| **Data Visualization** | ![Recharts](https://img.shields.io/badge/Recharts-8884D8?style=flat-square&logo=recharts&logoColor=white) |

### Development Tools

- 📦 **Package Manager**: pnpm
- 🧪 **Testing**: Vitest
- 📜 **Linting & Formatting**: ESLint + Prettier
- 🎨 **Icons**: Lucide React
- 📝 **Documentation**: VitePress

---

## 🖼️ Screenshots

> *Placeholder for screenshots - will be added after deployment*

| Dashboard | Interview Session | Feedback Report |
|-----------|-------------------|-----------------|
| ![Dashboard](/public/assets/img/hero.jpg) | ![Interview](/public/assets/img/office.jpg) | ![Feedback](/public/assets/img/bg.png) |

---

## 🚀 Installation

Follow these steps to set up the project locally:

### Prerequisites

- Node.js v18.0+ ([Download](https://nodejs.org))
- pnpm package manager ([Install](https://pnpm.io/installation))
- Firebase account ([Create one](https://firebase.google.com))
- Clerk account ([Create one](https://clerk.dev))
- Google Cloud account with Gemini API enabled ([Setup guide](https://ai.google.dev/gemini-api/docs/get-started/quickstart))

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ai-mock-interview.git
   cd ai-mock-interview
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Set up environment variables** (see next section)

4. **Start the development server**
   ```bash
   pnpm dev
   ```

5. **Open your browser** and navigate to `http://localhost:5173`

---

## ⚙️ Environment Variables (.env setup)

Create a `.env` file in the root directory with the following variables:

```env
# Firebase Configuration
VITE_FIREBASE_API_KEY=your-firebase-api-key
VITE_FIREBASE_AUTH_DOMAIN=your-project-id.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your-project-id
VITE_FIREBASE_STORAGE_BUCKET=your-project-id.appspot.com
VITE_FIREBASE_MESSAGING_SENDER_ID=your-sender-id
VITE_FIREBASE_APP_ID=your-app-id
VITE_FIREBASE_MEASUREMENT_ID=G-your-measurement-id

# Clerk Configuration
VITE_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
VITE_CLERK_SECRET_KEY=your-clerk-secret-key

# Google Gemini API
VITE_GEMINI_API_KEY=your-gemini-api-key

# Application Settings
VITE_APP_NAME=AI Mock Interview
VITE_APP_DESCRIPTION=AI-powered mock interview platform
```

> 💡 **Note**: Replace all placeholder values with your actual configuration keys. You can find these in your respective service dashboards.

---

## 🎮 How to Use

1. **Sign Up/Sign In**: Create an account using Clerk authentication
2. **Dashboard**: View your interview history and performance metrics
3. **Start Interview**: Select a role (e.g., Frontend Developer, Data Scientist) and experience level
4. **Interview Session**: 
   - AI generates questions based on your selection
   - Speak your answers while the system records audio and video
   - Review your responses before submitting
5. **Feedback Report**: 
   - View overall score (1-10)
   - Analyze strengths and areas for improvement
   - Download PDF report
6. **Track Progress**: Monitor your improvement over multiple interview sessions

---

## 📁 Project Structure

```
ai-mock-interview/
├── public/              # Static assets (images, fonts, etc.)
├── src/
│   ├── assets/          # Project-specific assets
│   ├── components/      # Reusable UI components
│   │   ├── ui/          # Shadcn UI components
│   │   └── ...          # Custom components
│   ├── config/          # Configuration files (Firebase, etc.)
│   ├── handlers/        # Authentication handlers
│   ├── layouts/         # Page layouts (auth, protected routes)
│   ├── lib/             # Utility functions and hooks
│   ├── provider/        # Context providers (Toast, etc.)
│   ├── routes/          # Page components and routing
│   ├── scripts/         # Entry point scripts
│   ├── types/           # TypeScript type definitions
│   ├── App.tsx          # Main application component
│   ├── index.css          # Global styles
│   └── main.tsx           # Entry point
├── .env                 # Environment variables
├── package.json         # Project dependencies and scripts
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite configuration
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository** and create your feature branch
2. **Install dependencies**: `pnpm install`
3. **Make your changes** and ensure they follow our coding standards
4. **Run tests**: `pnpm test` (if applicable)
5. **Commit your changes**: `pnpm commit` (follow our conventional commits)
6. **Push to your fork** and submit a pull request

### Contribution Guidelines

- Follow the [React Style Guide](https://react.dev/learn/your-first-component)
- Write descriptive commit messages
- Update documentation when adding new features
- Ensure code is properly typed with TypeScript
- Test your changes thoroughly before submitting

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact / Author

**Suryakant**
- 🎓 BTech CSE (AI & DS) Final Year Student
- 📧 suryakant@example.com
- 🔗 [LinkedIn](https://linkedin.com/in/suryakant)
- 🐙 [GitHub](https://github.com/suryakant)

> 💡 Have questions or suggestions? Feel free to reach out!

---

<p align="center">
  <b>Made with ❤️ and AI magic</b>
</p>