<div align="center">

# 💖 Project Aura 💖

*Your AI-Powered Dating Experience*

![React](https://img.shields.io/badge/React-19.1-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-0.119-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Latest-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-Platform-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**A modern, full-stack dating application featuring AI-powered personality analysis, real-time messaging, and intelligent matching algorithms.**

---

</div>

## 📖 Introduction

**Project Aura** is a next-generation dating platform that combines cutting-edge AI technology with intuitive user experience to help people find meaningful connections. Built with modern web technologies and deployed on Google Cloud Platform, Aura provides a seamless, secure, and engaging environment for users to discover, connect, and interact.

Our platform leverages advanced AI models from **Anthropic Claude** and **Google Gemini** to provide personalized experiences, from personality analysis during onboarding to relationship advice and intelligent chatbot assistance.

---

## ✨ Key Features

### 🤖 AI-Powered Personality Analysis
Understand yourself better with our sophisticated AI chatbot that analyzes your personality during the signup process.

- **Interactive conversational assessment** using Anthropic Claude Agent SDK
- **Real-time personality insights** based on natural language processing
- **Spider chart visualization** of personality traits
- **Personalized recommendations** based on analysis results

<details>
<summary>🎬 <b>View Personality Analysis Demo</b></summary>

> *"Our AI chatbot conducts a natural conversation to understand your unique personality, preferences, and relationship goals - providing insights that help create more meaningful matches."*

**Key Technologies:** Anthropic Claude SDK, React 19, Streaming responses

</details>

---

### 💬 Real-Time Messaging System
Stay connected with instant messaging powered by WebSocket technology.

- **Instant message delivery** using Socket.IO
- **Typing indicators** to show when someone is composing
- **Read receipts** for message status tracking
- **Message reactions** with emoji support
- **File and image sharing** via Google Cloud Storage
- **Chat history** with infinite scroll pagination

<details>
<summary>🎬 <b>View Messaging Demo</b></summary>

> *"Experience seamless, real-time conversations with your matches. Our WebSocket-powered chat ensures instant delivery, typing indicators, and rich media sharing."*

**Key Technologies:** Socket.IO, FastAPI WebSockets, React Context API

</details>

---

### 🎯 Intelligent Matching Algorithm
Find your perfect match with our AI-enhanced compatibility system.

- **Smart compatibility scoring** based on interests, preferences, and personality
- **Like/dislike swipe interface** with smooth animations
- **Mutual match detection** with instant notifications
- **Preference filtering** (age, distance, interests, education)
- **Match queue optimization** for better suggestions
- **Profile completion tracking** for quality matches

<details>
<summary>🎬 <b>View Matching Demo</b></summary>

> *"Our intelligent algorithm analyzes multiple factors including shared interests, personality compatibility, and user preferences to suggest the most compatible matches."*

**Key Technologies:** SQLAlchemy ORM, PostgreSQL, Custom scoring algorithms

</details>

---

### 🖼️ Advanced Profile Management
Create a stunning profile with our comprehensive setup flow.

- **Multi-step signup process** with progress tracking
- **Photo upload and cropping** with react-easy-crop
- **ID verification system** for authenticity
- **Voice recording setup** for personalized greetings
- **Interest selection** from curated categories
- **Profile completion percentage** tracking
- **Real-time profile preview**

<details>
<summary>🎬 <b>View Profile Setup Demo</b></summary>

> *"Build a comprehensive profile that truly represents you. Our step-by-step process includes photo editing, interest selection, and personality insights."*

**Key Technologies:** React Router DOM 7, Google Cloud Storage, Material UI

</details>

---

### 🧠 RAG-Powered Relationship Advice
Get personalized dating and relationship advice from our AI assistant.

- **Retrieval-Augmented Generation (RAG)** for contextual responses
- **Vector similarity search** using FAISS
- **Multi-source knowledge base** from relationship experts
- **Personalized advice** based on your profile and history
- **Conversation memory** for contextual follow-ups
- **Safe and ethical AI** with content filtering

<details>
<summary>🎬 <b>View AI Advisor Demo</b></summary>

> *"Our AI relationship advisor uses RAG technology to provide personalized, context-aware advice by retrieving relevant information from a curated knowledge base."*

**Key Technologies:** LangChain, FAISS, Sentence Transformers, Google Generative AI

</details>

---

### 📱 Progressive Web App (PWA)
Enjoy a native-app experience on any device.

- **Offline functionality** with service workers
- **App-like experience** on mobile and desktop
- **Add to home screen** capability
- **Push notifications** (coming soon)
- **Optimized caching strategies** with Workbox
- **CDN-powered media delivery** for fast loading
- **Responsive design** for all screen sizes

<details>
<summary>🎬 <b>View PWA Features Demo</b></summary>

> *"Install Aura on your device for a seamless app-like experience. Our PWA provides offline access, fast loading times, and native-like interactions."*

**Key Technologies:** Vite PWA Plugin, Workbox, Service Workers

</details>

---

### 🎨 Beautiful UI/UX
Experience modern design with smooth animations and intuitive navigation.

- **Dark/Light mode** with smooth transitions
- **Framer Motion animations** for delightful interactions
- **GSAP timeline animations** for complex sequences
- **Lottie animations** for engaging visuals
- **Tailwind CSS** for responsive design
- **Material UI components** for consistency
- **Custom theme system** with CSS variables

<details>
<summary>🎬 <b>View UI/UX Demo</b></summary>

> *"Every interaction in Aura is designed to delight. From match animations to smooth page transitions, we've crafted an experience that feels magical."*

**Key Technologies:** Framer Motion, GSAP, Lottie, Tailwind CSS, Material UI

</details>

---

### 🔒 Security & Privacy
Your safety is our top priority.

- **Bcrypt password hashing** for secure authentication
- **JWT token authentication** (implementation ready)
- **SQL injection prevention** with parameterized queries
- **CORS protection** for API security
- **Input validation** with Pydantic
- **Secure file uploads** to Google Cloud Storage
- **Privacy controls** for profile visibility

---

## 🛠️ Tech Stack Overview

### 🎨 Front-End
- **React 19** - Latest version with modern features
- **Vite 7** - Lightning-fast build tool
- **React Router DOM 7.9** - Advanced routing and navigation
- **Tailwind CSS 3.4** - Utility-first CSS framework
- **Material UI 7.3** - Comprehensive component library
- **Socket.IO Client 4.8** - Real-time WebSocket communication
- **Axios 1.12** - Promise-based HTTP client
- **Framer Motion** - Production-ready motion library
- **GSAP** - Professional-grade animation
- **Lottie React** - JSON-based animations
- **React Easy Crop** - Image cropping component

### ⚙️ Back-End
- **FastAPI 0.119** - Modern Python web framework
- **Uvicorn 0.37** - ASGI server with WebSocket support
- **SQLAlchemy 2.0** - Python SQL toolkit and ORM
- **Pydantic 2.12** - Data validation using Python type annotations
- **Python Socket.IO 5.11** - WebSocket server implementation
- **Alembic 1.13** - Database migration tool
- **Passlib + Bcrypt** - Password hashing library
- **Python-Jose** - JWT token handling (ready for implementation)

### 🤖 AI & Machine Learning
- **Anthropic Claude Agent SDK 0.1.29** - Advanced AI chatbot
- **Google Generative AI (Gemini)** - Multi-modal AI capabilities
- **LangChain 0.3** - AI orchestration framework
- **FAISS** - Vector similarity search (Facebook AI)
- **Sentence Transformers 3.3** - Semantic embeddings
- **ChromaDB 0.4** - Vector database for RAG

### 💾 Storage & Database
- **PostgreSQL** - Relational database with advanced features
- **Google Cloud SQL** - Managed PostgreSQL hosting
- **Google Cloud Storage** - CDN for media files
- **CITEXT** - Case-insensitive text columns
- **JSONB** - Flexible JSON storage in PostgreSQL

### 🚀 Infrastructure & Deployment
- **Google Cloud Platform** - Cloud hosting and services
- **Firebase Hosting** - Frontend deployment
- **GitLab CI/CD** - Auto DevOps pipeline
- **Cloud SQL Auth Proxy** - Secure database connections
- **Gmail API** - Email notifications
- **Vite PWA Plugin** - Progressive Web App support

### 🧪 Development Tools
- **ESLint 9** - JavaScript/React linting
- **Black** - Python code formatter
- **Flake8** - Python style guide enforcement
- **Pytest** - Python testing framework
- **PostCSS** - CSS transformation tool

---

## 🏗️ Project Architecture

### Frontend Architecture
```
frontend/
├── src/
│   ├── components/
│   │   ├── Auth/           # Authentication & protected routes
│   │   ├── Chat/           # Real-time messaging components
│   │   ├── Discover/       # Matching and swiping interface
│   │   ├── Like/           # Like management pages
│   │   ├── Main/           # Main app pages and settings
│   │   ├── Match/          # Match animations
│   │   ├── Report/         # Reporting and security
│   │   ├── SignUp/         # Multi-step signup flow
│   │   ├── common/         # Reusable components
│   │   └── premium/        # Premium features
│   ├── api/
│   │   └── services/       # API service layer
│   ├── contexts/           # React contexts (Socket, Toast)
│   ├── hooks/              # Custom React hooks
│   └── utils/              # Utility functions
├── vite.config.js          # Vite configuration
└── tailwind.config.js      # Tailwind customization
```

### Backend Architecture
```
backend/
├── app/
│   ├── routes/             # API endpoints
│   │   ├── users.py        # User management
│   │   ├── profiles.py     # Profile operations
│   │   ├── messages.py     # Chat messaging
│   │   ├── matches.py      # Matching system
│   │   ├── likes.py        # Like/dislike operations
│   │   ├── ai.py           # AI chatbot endpoints
│   │   └── advice.py       # Relationship advice
│   ├── crud/               # Database operations
│   ├── schemas/            # Pydantic models
│   ├── models.py           # SQLAlchemy models
│   ├── services/           # Business logic
│   │   ├── ai_service.py   # AI integration
│   │   ├── ai_agents.py    # AI agent definitions
│   │   └── rag_store.py    # RAG implementation
│   ├── utils/              # Utility functions
│   │   ├── gcs.py          # Google Cloud Storage
│   │   ├── gmail_api_service.py  # Email sending
│   │   └── notification_service.py
│   ├── database.py         # Database configuration
│   ├── websocket.py        # WebSocket event handlers
│   └── main.py             # FastAPI app initialization
└── migrations/             # Alembic migrations
```

---

## 🚀 Getting Started

### Prerequisites
- **Node.js 18+** and npm
- **Python 3.11+**
- **PostgreSQL** (local or Google Cloud SQL access)
- **Google Cloud Account** (for storage and deployment)

### Backend Setup

1. **Navigate to backend directory:**
   ```bash
   cd Project-Aura-Development/backend
   ```

2. **Create virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate virtual environment:**
   - Windows: `.venv\Scripts\activate`
   - macOS/Linux: `source .venv/bin/activate`

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Configure environment variables:**
   - Copy `.env.example` to `.env`
   - Fill in database credentials and API keys

6. **Start the server:**
   ```bash
   uvicorn app.main:app --reload --port 8000
   ```

### Frontend Setup

1. **Navigate to frontend directory:**
   ```bash
   cd Project-Aura-Development/frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   - Create `frontend/.env`
   - Set `VITE_API_BASE_URL=http://localhost:8000`

4. **Start development server:**
   ```bash
   npm run dev
   ```

5. **Open in browser:**
   - Navigate to `http://localhost:5173/`

---

## 📊 Database Schema Highlights

### Core Models
- **User** - Authentication and basic info
- **Profile** - Extended user profile with interests
- **Message** - Chat messages with attachments
- **ChatSession** - Message grouping
- **LikeDislike** - Swipe actions
- **Match** - Mutual likes
- **ProfileAnalysis** - Personality insights
- **AIChatMemory** - Conversation history

### Relationships
- One-to-One: User ↔ Profile, User ↔ ProfileAnalysis
- One-to-Many: User → Messages, User → Likes
- Many-to-Many: User ↔ Interests, User ↔ Languages

---

## 📈 Performance Optimizations

### Recent Achievements
- ✅ **60% improvement** in AI chatbot response time
- ✅ **Optimized message caching** for faster chat loading
- ✅ **CDN-powered media delivery** for images and videos
- ✅ **Code splitting** for reduced initial bundle size
- ✅ **Service worker caching** for offline support

### Key Optimizations
1. **Frontend:**
   - Lazy loading routes
   - Image optimization and lazy loading
   - Memoization of expensive calculations
   - Virtual scrolling for long lists

2. **Backend:**
   - Database query optimization with indexes
   - Connection pooling
   - Async/await for concurrent operations
   - Response caching for static data

---

## 🧪 Testing

### Backend Testing
```bash
# Run all tests
pytest

# Test specific module
pytest backend/scripts/test_api.py

# Test with coverage
pytest --cov=app
```

### Frontend Testing
```bash
# Run linter
npm run lint

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 🚢 Deployment

### Backend (Google Cloud Platform)
1. Set up Cloud SQL instance
2. Configure Cloud Storage bucket
3. Deploy via GitLab CI/CD or manual deployment
4. Configure environment variables in Cloud Run/Compute Engine

### Frontend (Firebase Hosting)
```bash
# Build for production
npm run build

# Deploy to Firebase
firebase deploy
```

### CI/CD Pipeline
- Automated testing on every commit
- Secret detection enabled
- Deployment to staging/production environments
- GitLab Auto DevOps integration

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
2. **Create a feature branch:**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes and commit:**
   ```bash
   git commit -m "Add amazing feature"
   ```
4. **Push to your branch:**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style
- Add comments for complex logic
- Write tests for new features
- Update documentation as needed
- Get code review before merging to main

---

## 📝 API Documentation

Once the backend is running, visit:
- **Swagger UI:** `http://localhost:8000/docs`
- **ReDoc:** `http://localhost:8000/redoc`

### Key Endpoints
- `POST /users/register` - User registration
- `POST /users/login` - User authentication
- `GET /users/{id}` - Get user profile
- `POST /profiles/` - Create profile
- `POST /messages/` - Send message
- `POST /likes/` - Like/dislike user
- `GET /matches/` - Get matches
- `POST /ai/chat` - AI chatbot interaction

---

## 🗺️ Roadmap

### Upcoming Features
- [ ] JWT authentication implementation
- [ ] Push notifications for mobile
- [ ] Video call integration
- [ ] Advanced analytics dashboard
- [ ] Premium subscription features
- [ ] Enhanced AI matching algorithm
- [ ] Group chat functionality
- [ ] Story/feed feature
- [ ] Location-based matching improvements

---

## 👥 Team

**Project Aura Development Team**
- Backend Architecture: Christian Lew
- Full-Stack Development: Team Contributors
- AI Integration: AI/ML Team
- UI/UX Design: Design Team

---

## 🙏 Acknowledgments

### Open Source Projects
- **React Team** - For the amazing React framework
- **FastAPI** - For the modern Python web framework
- **Anthropic** - For Claude AI capabilities
- **Google** - For Gemini AI and Cloud Platform
- **LangChain** - For AI orchestration tools
- **All contributors** to the libraries we use

### Special Thanks
- **Gamuda AI Academy** - For support and guidance
- **Open Source Community** - For invaluable tools and libraries

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact & Support

- **Report Issues:** [GitHub Issues](https://github.com/your-repo/project-aura/issues)
- **Email:** support@aura-dating-app.com
- **Documentation:** [Full Documentation](https://docs.aura-dating-app.com)

---

<div align="center">

**Built with ❤️ by the Project Aura Team**

*Connecting hearts with technology*

</div>
