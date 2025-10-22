# 🧠 Mental Health Digital Support System

A Smart India Hackathon 2025 project by **Team IgniteCodeX**

A comprehensive **Digital Mental Health & Psychological Support System** designed to assist students in higher education with AI-driven mental health insights, multilingual chatbot support, and real-time analytics.

##Project Structure
- Mental-Health-Digital-Support-System/
  - web/
    - public/
      - index.html
      - assets/
    - src/
      - components/
        - Navbar.jsx
        - Footer.jsx
        - ChatbotUI.jsx
        - Dashboard/
        - Forms/
      - pages/
        - Home.jsx
        - Resources.jsx
        - PeerForum.jsx
        - CounsellorBooking.jsx
        - AdminDashboard.jsx
      - hooks/
        - useAuth.js
      - context/
        - AuthContext.js
      - services/
        - api.js
        - chatbotService.js
        - bookingService.js
        - analyticsService.js
      - App.jsx
      - main.jsx
      - index.css
    - package.json
    - tailwind.config.js
    - README.md
  - app/
    - src/
      - screens/
        - SplashScreen.js
        - LoginScreen.js
        - ChatbotScreen.js
        - MoodTracker.js
        - ForumScreen.js
        - BookingScreen.js
        - ProfileScreen.js
      - components/
        - ChatBubble.js
        - MoodCard.js
        - ResourceCard.js
        - Loader.js
      - navigation/
        - AppNavigator.js
      - utils/
        - api.js
      - context/
        - AuthContext.js
      - assets/
        - icons/
        - images/
    - app.json
    - package.json
    - README.md
  - backend/
    - node-api/
      - src/
        - routes/
          - auth.js
          - user.js
          - booking.js
          - analytics.js
        - controllers/
        - models/
          - User.js
        - middleware/
          - auth.js
        - app.js
      - package.json
      - .env
  - ai-service/
    - app/
      - main.py
      - routes/
        - chatbot.py
      - services/
        - llama_model.py
        - sentiment.py
      - tasks/
        - celery_tasks.py
      - utils/
    - requirements.txt
    - Dockerfile
  - docker-compose.yml
  - kubernetes/
    - deployment.yaml
    - service.yaml
    - ingress.yaml
  - README.md

## 👥 Team Roles

| Role | Responsibility |
|------|----------------|
| Frontend Developer|Web UI using React + Tailwind|| Mobile Developer | React Native mobile app with offline mode |
| Backend Developer | Node.js REST API, authentication, database |
| AI Developer | FastAPI + LLaMA chatbot & sentiment analysis |
| Analytics Developer | Trend analytics, charts, and admin insights |
| DevOps Engineer | Docker, Kubernetes, CI/CD pipeline setup |
