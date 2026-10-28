<div align="center">

# 🎯 Nex inter AI

### *AI-Powered Mock Interview Platform with Intelligent Feedback & Resume Optimization*

[![Next.js](https://img.shields.io/badge/Next.js-15.4-black?style=flat&logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB?style=flat&logo=react&logoColor=black)](https://reactjs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Latest-47A248?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Firebase](https://img.shields.io/badge/Firebase-12.0-FFCA28?style=flat&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](LICENSE)

[Features](#-features) • [Quick Start](#-quick-start) • [Tech Stack](#-tech-stack) • [Documentation](#-documentation) • [Contributing](#-contributing)

---

<!-- 
🎨 ADD YOUR BANNER IMAGE HERE
![NexPrep AI Banner](./public/banner.png)
-->

</div>

## 📖 Overview

**NexPrep AI** is a cutting-edge mock interview platform that leverages AI to simulate real-world interview scenarios. Get personalized feedback, optimize your resume for ATS systems, and build professional resumes—all in one place. Perfect for job seekers preparing for technical interviews, behavioral assessments, and career transitions.

### Why This Platform?

| Feature | Description |
|---------|-------------|
| 🎤 **Real-Time Voice Interviews** | Conduct natural voice-based interviews with AI using speech-to-text and synthesis technology |
| 🤖 **Smart Question Generation** | AI generates tailored questions based on job role, experience level, and difficulty |
| 📊 **Actionable Feedback** | Receive detailed performance metrics, ratings, and improvement suggestions after each interview |
| 📄 **ATS Resume Checker** | Analyze your resume for ATS compatibility with rule-based scoring and AI insights |
| ✏️ **Professional Resume Builder** | Create stunning resumes with 4 customizable templates (Modern, Professional, Creative, Executive) |
| 🔐 **Secure & Private** | Firebase authentication with encrypted data storage in MongoDB |

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/NexPrep-main.git
cd NexPrep-main

# Install dependencies
npm install

# Set up environment variables (see .env.local example below)
cp .env.example .env.local

# Run development server
npm run dev
# Visit http://localhost:3000
```

> 📚 For detailed setup instructions, see [Installation Guide](#-installation)

---

<details>
<summary>🖼️ <strong>View Screenshots</strong></summary>

<!-- 
Add your screenshots here:
![Dashboard](./screenshots/dashboard.png)
![Interview](./screenshots/interview.png)
![ATS Checker](./screenshots/ats-checker.png)
![Resume Builder](./screenshots/resume-builder.png)
-->

</details>

---

## 📑 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Deployment](#-deployment)
- [Testing](#-testing)
- [Documentation](#-documentation)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Support](#-support)

---

## ✨ Features

<table>
<tr>
<td valign="top" width="50%">

### 🎤 Interview System
- **AI Mock Interviews**
  - Voice-based real-time interactions
  - Customizable duration (15/30/45/60 min)
  - Three difficulty levels (Easy/Medium/Hard)
  - Webcam recording support
  - Automatic question generation
  
- **Intelligent Feedback**
  - Detailed performance analytics
  - Rating system (1-10 scale)
  - Improvement suggestions
  - Historical tracking

### 📊 Dashboard & Analytics
- Interview history tracking
- Performance metrics visualization
- Questions solved counter
- Average score calculations
- Quick action cards

</td>
<td valign="top" width="50%">

### 📄 Resume Tools
- **ATS Checker**
  - PDF & DOCX support
  - Rule-based scoring (Structure, Impact, Skills)
  - Missing sections detection
  - Contact info validation
  - Actionable recommendations
  
- **Resume Builder**
  - 4 professional templates
  - Real-time preview
  - Customizable sections
  - Export-ready formats
  - Template switching

### 🔐 User Management
- Firebase email/password authentication
- Secure session management
- User-specific data isolation
- Profile management

</td>
</tr>
</table>

---

## 🛠 Tech Stack

### Core Technologies

![Next.js](https://img.shields.io/badge/Next.js-15.4-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-19.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & Database

![MongoDB](https://img.shields.io/badge/MongoDB-Latest-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-9.2-880000?style=for-the-badge&logo=mongoose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-12.0-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### AI & Integrations

![Google AI](https://img.shields.io/badge/Google_Gemini-AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Grok API](https://img.shields.io/badge/Grok_API-xAI-000000?style=for-the-badge&logo=x&logoColor=white)

---

<details>
<summary><strong>📋 Complete Technology Breakdown</strong></summary>

### Frontend
| Technology | Purpose | Version |
|------------|---------|---------|
| **Next.js** | React framework with SSR/SSG | 15.4.1 |
| **React** | UI library | 19.2.4 |
| **TypeScript** | Type safety | 5.8.3 |
| **Tailwind CSS** | Utility-first styling | Latest |
| **Framer Motion** | Animations | 12.23.9 |
| **Radix UI** | Headless UI components | Latest |
| **Lucide React** | Icon library | 0.525.0 |
| **React Webcam** | Camera integration | 7.2.0 |

### Backend & Database
| Technology | Purpose |
|------------|---------|
| **MongoDB** | NoSQL database |
| **Mongoose** | ODM for MongoDB |
| **Firebase Auth** | User authentication |
| **Firebase Admin** | Server-side Firebase SDK |

### AI & Processing
| Technology | Purpose |
|------------|---------|
| **Grok API (xAI)** | Primary AI for question generation |
| **Google Gemini AI** | Alternative AI provider |
| **react-speech-to-text** | Voice input |
| **Web Speech API** | Text-to-speech synthesis |

### File Processing
| Technology | Purpose |
|------------|---------|
| **pdf-parse** | PDF parsing |
| **mammoth** | DOCX parsing |

### DevOps & Deployment
| Technology | Purpose |
|------------|---------|
| **Vercel** | Hosting & CI/CD |
| **Turbopack** | Fast bundler (dev) |
| **ESLint** | Code linting |

</details>

---

## 🏗 Architecture

```mermaid
graph TB
    A[User Browser] -->|HTTPS| B[Next.js Frontend]
    B -->|Route Handlers| C[API Routes]
    C -->|Authentication| D[Firebase Auth]
    C -->|Data Queries| E[MongoDB]
    C -->|AI Requests| F[Grok API / Gemini AI]
    B -->|Real-time Voice| G[Web Speech API]
    B -->|File Upload| H[File Parser]
    H -->|PDF/DOCX| C
    E -->|Mongoose ODM| I[Data Models]
    
    style A fill:#61DAFB,stroke:#333,stroke-width:2px
    style B fill:#000000,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#FFCA28,stroke:#333,stroke-width:2px
    style E fill:#47A248,stroke:#333,stroke-width:2px,color:#fff
    style F fill:#4285F4,stroke:#333,stroke-width:2px,color:#fff
```

### Design Patterns

| Pattern | Implementation | Purpose |
|---------|---------------|---------|
| **Server Actions** | `app/actions/*.js` | Server-side data mutations with Next.js 15 |
| **Component Composition** | Radix UI + ShadCN | Reusable, accessible UI components |
| **Singleton Pattern** | `firebase/client.js`, `utils/mongodb.js` | Single database/auth instance |
| **Factory Pattern** | `utils/GeminiAIModal.js` | AI provider abstraction |
| **MVC Architecture** | Models (`utils/models.js`) + Controllers (Actions) + Views (Components) | Separation of concerns |

---

## 📥 Installation

### Prerequisites

- **Node.js** >= 18.0.0
- **npm** or **yarn**
- **MongoDB Atlas** account (free tier available)
- **Firebase** project
- **AI API Key** (Grok/Gemini)

---

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/NexPrep-main.git
cd NexPrep-main
```

---

### 2️⃣ Install Dependencies

```bash
npm install
# or
yarn install
```

---

### 3️⃣ Environment Configuration

Create a `.env.local` file in the root directory:

```env
# MongoDB
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/nexprep
NEXT_PUBLIC_MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/nexprep

# AI Provider (Choose one or both)
NEXT_PUBLIC_GROK_API_KEY=xai-xxxxxxxxxxxxxx
# OR
NEXT_PUBLIC_GEMINI_API_KEY=AIzaSyxxxxxxxxxxxxx

# Firebase Admin SDK (Server-side)
FIREBASE_PROJECT_ID=your-project-id
FIREBASE_CLIENT_EMAIL=firebase-adminsdk-xxxxx@your-project-id.iam.gserviceaccount.com
FIREBASE_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\nYourPrivateKey\n-----END PRIVATE KEY-----\n"

# Firebase Client (Public)
NEXT_PUBLIC_FIREBASE_API_KEY=AIzaSyxxxxxxxxxxxxx
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-project-id.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-project-id.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=123456789012
NEXT_PUBLIC_FIREBASE_APP_ID=1:123456789012:web:abcdef123456
```

**Where to get credentials:**
- 🗄️ MongoDB: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- 🤖 Grok API: [xAI Console](https://console.x.ai/)
- 🤖 Gemini AI: [Google AI Studio](https://makersuite.google.com/app/apikey)
- 🔥 Firebase: [Firebase Console](https://console.firebase.google.com/) → Project Settings → Service Accounts

---

### 4️⃣ Database Setup

```bash
# Optional: Seed demo data
node scripts/seed_demo_feedback.mjs
```

The MongoDB collections (`mockinterviews`, `useranswers`) will be created automatically on first run.

---

### 5️⃣ Run Development Server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

<details>
<summary><strong>🐳 Docker Setup (Alternative)</strong></summary>

```dockerfile
# Dockerfile
FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
```

```bash
# Build and run
docker build -t nexprep-ai .
docker run -p 3000:3000 --env-file .env.local nexprep-ai
```

</details>

---

<details>
<summary><strong>🔧 Common Installation Issues</strong></summary>

**Issue:** `Module not found: Can't resolve 'firebase'`
```bash
# Solution: Reinstall dependencies
rm -rf node_modules package-lock.json
npm install
```

**Issue:** `Firebase: Error (auth/invalid-api-key)`
```bash
# Solution: Check that NEXT_PUBLIC_FIREBASE_API_KEY is correctly set
# Ensure no extra spaces or quotes in .env.local
```

**Issue:** `MongooseServerSelectionError`
```bash
# Solution: Whitelist your IP in MongoDB Atlas
# Network Access → Add IP Address → Allow Access from Anywhere (0.0.0.0/0)
```

**Issue:** `Grok API Error: 401 Unauthorized`
```bash
# Solution: Verify your API key
# Ensure NEXT_PUBLIC_GROK_API_KEY starts with 'xai-'
```

</details>

---

## 🎯 Usage

### Interview Workflow

```mermaid
sequenceDiagram
    participant U as User
    participant D as Dashboard
    participant AI as AI Engine
    participant DB as Database
    participant V as Voice System

    U->>D: Create New Interview
    D->>AI: Generate Questions (Job Details)
    AI-->>D: Return Interview Questions
    D->>DB: Save Interview
    U->>V: Start Voice Interview
    V->>U: Ask Question (Speech Synthesis)
    U->>V: Answer (Speech-to-Text)
    V->>AI: Analyze Answer
    AI-->>V: Return Feedback & Rating
    V->>DB: Save User Answer
    U->>D: View Feedback Report
```

---

### Step-by-Step Guide

#### 1️⃣ Create Mock Interview

1. Navigate to **Dashboard**
2. Click **"+ Add New Interview"**
3. Fill in:
   - **Job Position** (e.g., "Frontend Developer")
   - **Job Description** (paste JD or key responsibilities)
   - **Years of Experience**
   - **Location** (optional)
   - **Duration** (15/30/45/60 minutes)
   - **Difficulty** (Easy/Medium/Hard)
4. Click **"Start Interview"**

#### 2️⃣ Conduct Interview

1. Click **"Start Recording"** to enable webcam
2. Grant microphone & camera permissions
3. Click on each question to hear it read aloud
4. Speak your answer clearly
5. Click **"Stop Recording"** when done
6. Review your recorded answer
7. Click **"Submit & Get Feedback"**
8. View AI-generated feedback and ratings

#### 3️⃣ Check ATS Score

1. Go to **"ATS Checker"** tab
2. Upload your resume (PDF/DOCX)
3. Review your score breakdown:
   - Structure (15%)
   - Impact (25%)
   - Skills (30%)
   - Style (20%)
   - Brevity (10%)
4. Read detailed suggestions
5. Download optimized resume

#### 4️⃣ Build Resume

1. Navigate to **"Resume Builder"**
2. Select a template
3. Fill in your details:
   - Personal Info
   - Professional Summary
   - Experience
   - Education
   - Skills
   - Projects
4. Preview in real-time
5. Export or print

---

### Configuration Parameters

| Parameter | Options | Description |
|-----------|---------|-------------|
| **Interview Duration** | 15, 30, 45, 60 min | Total interview time |
| **Difficulty Level** | Easy, Medium, Hard | Question complexity |
| **Interview Mode** | Voice, Text | Input method (Voice recommended) |
| **Voice Language** | en-US, en-GB, etc. | Speech synthesis language |

---

<details>
<summary><strong>⚙️ Advanced Configuration</strong></summary>

### Custom AI Prompts

Edit [`utils/GeminiAIModal.js`](utils/GeminiAIModal.js) to customize AI behavior:

```javascript
export const chatSession = {
  sendMessage: async (inputPrompt) => {
    // Modify temperature (0.0 - 1.0)
    // Higher = more creative, Lower = more focused
    const response = await fetch("https://api.x.ai/v1/chat/completions", {
      body: JSON.stringify({
        model: "grok-beta",
        temperature: 0.7, // Adjust here
        // ... rest of config
      })
    });
  }
};
```

### Database Schema Customization

Modify [`utils/models.js`](utils/models.js) to add custom fields:

```javascript
const MockInterviewSchema = new mongoose.Schema({
  // Add your custom fields
  customField: { type: String, maxlength: 500 },
  // ... existing fields
});
```

</details>

---

## 📂 Project Structure

```
NexPrep-main/
│
├── app/                          # Next.js App Router
│   ├── actions/                  # Server Actions
│   │   └── interview.js          # Interview CRUD operations
│   ├── auth/                     # Authentication pages
│   │   ├── sign-in/
│   │   └── sign-up/
│   ├── dashboard/                # Main application
│   │   ├── _components/          # Dashboard components
│   │   │   ├── AddNewInterview.jsx      # Interview creation modal
│   │   │   ├── InterviewList.jsx        # Interview history
│   │   │   └── Header.jsx               # Top navigation
│   │   ├── ats-checker/          # ATS resume analysis
│   │   │   └── _actions/
│   │   │       ├── analyze.js    # Rule-based ATS scoring
│   │   │       └── fileParser.js # PDF/DOCX parsing
│   │   ├── interview/
│   │   │   └── [interviewid]/
│   │   │       ├── start/        # Interview conduct page
│   │   │       └── feedback/     # Results & analytics
│   │   ├── questions/            # Question bank
│   │   ├── resume/               # Resume builder
│   │   │   └── _components/
│   │   │       └── templates/    # 4 resume templates
│   │   └── upgrade/              # Pricing (if applicable)
│   ├── globals.css               # Global styles
│   ├── layout.js                 # Root layout
│   └── page.js                   # Home (redirects to sign-in)
│
├── components/                   # Shared UI components
│   └── ui/                       # ShadCN UI components
│       ├── button.jsx
│       ├── dialog.jsx
│       ├── input.jsx
│       └── ...
│
├── firebase/                     # Firebase configuration
│   ├── admin.js                  # Server-side SDK
│   └── client.js                 # Client-side SDK
│
├── lib/
│   └── utils.js                  # Utility functions (cn helper)
│
├── public/                       # Static assets
│
├── scripts/                      # Database seeding scripts
│   ├── seed.mjs
│   ├── seed_feedback.mjs
│   └── seed_demo_feedback.mjs
│
├── utils/                        # Core utilities
│   ├── db.js                     # Database connection helper
│   ├── GeminiAIModal.js          # AI provider abstraction
│   ├── GeminiATS.js              # ATS AI analysis
│   ├── models.js                 # Mongoose schemas
│   ├── mongodb.js                # MongoDB singleton
│   └── schema.js                 # Validation schemas
│
├── .env.local                    # Environment variables (create this)
├── components.json               # ShadCN UI config
├── jsconfig.json                 # JavaScript config
├── next.config.mjs               # Next.js configuration
├── package.json                  # Dependencies
├── postcss.config.mjs            # PostCSS config
├── tailwind.config.js            # Tailwind CSS config
└── tsconfig.json                 # TypeScript config
```

---

## 🚀 Deployment

### Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/NexPrep-main)

1. Push your code to GitHub
2. Import project to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy automatically

**Environment Variables:**
- Go to **Project Settings** → **Environment Variables**
- Add all variables from `.env.local`
- Redeploy

---

### Other Platforms

<details>
<summary><strong>Netlify</strong></summary>

```bash
npm run build
```

Add `netlify.toml`:

```toml
[build]
  command = "npm run build"
  publish = ".next"

[[plugins]]
  package = "@netlify/plugin-nextjs"
```

</details>

<details>
<summary><strong>Docker + Cloud Run</strong></summary>

```bash
# Build
docker build -t nexprep-ai .

# Tag
docker tag nexprep-ai gcr.io/YOUR_PROJECT/nexprep-ai

# Push
docker push gcr.io/YOUR_PROJECT/nexprep-ai

# Deploy to Cloud Run
gcloud run deploy nexprep-ai \
  --image gcr.io/YOUR_PROJECT/nexprep-ai \
  --platform managed \
  --region us-central1 \
  --allow-unauthenticated
```

</details>

---

### Production Checklist

- [ ] Set `NODE_ENV=production`
- [ ] Enable Firebase Auth production mode
- [ ] Whitelist production domain in Firebase Console
- [ ] Update MongoDB IP whitelist
- [ ] Configure CORS if using custom domain
- [ ] Enable HTTPS
- [ ] Set up error monitoring (Sentry, LogRocket)
- [ ] Configure CDN for static assets
- [ ] Test all API endpoints in production
- [ ] Set up backup strategy for MongoDB

---

## 🧪 Testing

### Run Tests

```bash
# Frontend tests
npm run test

# End-to-end tests (if configured)
npm run test:e2e

# Linting
npm run lint
```

### Manual Testing Checklist

**Authentication**
- [ ] Sign up with email/password
- [ ] Sign in with existing account
- [ ] Sign out functionality
- [ ] Protected routes redirect to sign-in

**Interview Flow**
- [ ] Create new interview
- [ ] Start interview session
- [ ] Record voice answers
- [ ] Submit answers and get feedback
- [ ] View feedback report

**ATS Checker**
- [ ] Upload PDF resume
- [ ] Upload DOCX resume
- [ ] View ATS score breakdown
- [ ] Download suggestions

**Resume Builder**
- [ ] Switch between templates
- [ ] Enter resume data
- [ ] Preview updates in real-time
- [ ] Export resume

---

## 📚 Documentation

- [Installation Guide](#-installation)
- [Usage Guide](#-usage)
- [API Reference](#-architecture) (See Server Actions in `app/actions/`)
- [Contributing Guidelines](#-contributing)
- [Troubleshooting](#common-installation-issues)

---

## 🗺 Roadmap

### ✅ Completed

- [x] AI-powered mock interviews with voice input
- [x] Real-time feedback and rating system
- [x] ATS resume checker with rule-based scoring
- [x] Resume builder with 4 templates
- [x] Firebase authentication
- [x] MongoDB data persistence
- [x] Dashboard analytics
- [x] Webcam recording support

### 🚧 In Progress

- [ ] Multi-language support (i18n)
- [ ] Advanced analytics dashboard with charts
- [ ] Email notifications for interview reminders
- [ ] Export interview transcripts to PDF
- [ ] Mobile app (React Native)

### 📅 Planned

- [ ] Video-based interviews (recorded video analysis)
- [ ] Peer-to-peer mock interviews
- [ ] Interview marketplace (connect with mentors)
- [ ] AI-powered resume optimization (automatic rewriting)
- [ ] Integration with job boards (LinkedIn, Indeed)
- [ ] Company-specific interview prep (FAANG, MAANG)
- [ ] Behavioral interview questions database
- [ ] Progress tracking with gamification
- [ ] Chrome extension for quick practice
- [ ] Slack/Discord bot for interview reminders

**Want a feature?** [Open an issue](https://github.com/yourusername/NexPrep-main/issues/new) or contribute!

---

## 🤝 Contributing

<div align="center">

![Contributors](https://img.shields.io/github/contributors/yourusername/NexPrep-main?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/yourusername/NexPrep-main?style=for-the-badge)
![Pull Requests](https://img.shields.io/github/issues-pr/yourusername/NexPrep-main?style=for-the-badge)

</div>

We welcome contributions! Follow these steps:

### 1️⃣ Fork the Repository

Click the **Fork** button at the top right of this page.

### 2️⃣ Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/NexPrep-main.git
cd NexPrep-main
```

### 3️⃣ Create a Feature Branch

```bash
git checkout -b feature/amazing-feature
```

### 4️⃣ Make Your Changes

- Write clean, readable code
- Follow existing code style
- Add comments for complex logic
- Test your changes locally

### 5️⃣ Commit Your Changes

```bash
git add .
git commit -m "feat: add amazing feature"
```

**Commit Convention:**
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting)
- `refactor:` Code refactoring
- `test:` Adding tests
- `chore:` Maintenance tasks

### 6️⃣ Push to Your Fork

```bash
git push origin feature/amazing-feature
```

### 7️⃣ Open a Pull Request

- Go to the original repository
- Click **"New Pull Request"**
- Select your branch
- Describe your changes clearly
- Submit for review

---

### Contribution Guidelines

| Do ✅ | Don't ❌ |
|-------|----------|
| Write descriptive commit messages | Commit directly to `main` |
| Test your changes thoroughly | Submit untested code |
| Update documentation if needed | Introduce breaking changes without discussion |
| Follow existing code patterns | Ignore linting errors |
| Keep PRs focused and small | Bundle multiple unrelated changes |
| Be respectful in discussions | Use offensive language |

---

### Development Setup

```bash
# Install dependencies
npm install

# Run in development mode
npm run dev

# Build for production
npm run build

# Run production build locally
npm run start

# Lint code
npm run lint
```

---

## 💬 Support

- **Documentation**: Read the [Usage Guide](#-usage)
- **Issues**: Report bugs or request features on [GitHub Issues](https://github.com/yourusername/NexPrep-main/issues)

---

## 📄 License

<div align="center">

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

### Made with ❤️ by [Ajinkya](https://github.com/ajinkya2004)

🔗 **Live Demo**: [https://nexprep-ai.vercel.app](https://nexprep-ai.vercel.app/auth/sign-in)  
🔗 **Portfolio**: [https://itsajinkya.vercel.app](https://itsajinkya.vercel.app)  
📫 **LinkedIn**: [linkedin.com/in/ajinkya2004](https://www.linkedin.com/in/ajinkya2004)

⭐ **Star this repo** if you find it helpful!

[Back to Top](#-nexprep-ai)

</div>
