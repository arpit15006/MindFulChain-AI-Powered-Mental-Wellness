
# 🧠 MindfulChain - AI-Powered Mental Wellness Platform

> Transform your mental wellness journey with AI-powered insights, gamified assessments, and blockchain-verified achievements.

![MindfulChain](/public/logo.png)

## ✨ Features

### 🎮 Gamified Mental Health Assessment
- **Interactive Card-Based Evaluation**: Drag and drop emotion cards into frequency buckets
- **Multi-Category Assessment**: Mood, Sleep, Stress, Focus, and Energy evaluation
- **Beautiful UI/UX**: Smooth animations and modern gradient design
- **Progress Tracking**: Visual progress bar with step-by-step navigation
- **Reset Functionality**: Start fresh anytime with complete state reset

### 🤖 AI-Powered Insights & Chat
- **Google Gemini Integration**: Advanced AI provides personalized mental health feedback
- **AI Therapist Chat**: 24/7 conversational support with contextual responses
- **Empathetic Responses**: Warm, supportive, and actionable guidance
- **Multi-language Support**: Global accessibility through AI translation
- **Conversation History**: Persistent chat sessions with memory

### 🎯 Wellness Games & Activities
- **Memory Game**: Cognitive training with pattern recognition
- **Reaction Time Test**: Measure and improve response speed
- **Math Lightning**: Mental arithmetic challenges for brain training
- **Breathing Exercise**: Guided meditation and relaxation techniques
- **Score Tracking**: Progress monitoring across all games
- **Achievement System**: Unlock milestones and track improvements

### 🔗 Blockchain Rewards System
- **MINDFUL Tokens**: Earn ERC-20 tokens for consistent wellness tracking
- **Base Sepolia Network**: Secure, fast, and eco-friendly blockchain integration
- **Achievement NFTs**: Collect wellness milestone badges as ERC-1155 tokens
- **Wallet Integration**: MetaMask connection for seamless transactions
- **NFT Gallery**: View and showcase your wellness achievements

### 👤 Comprehensive User Profiles
- **Personal Dashboard**: Complete wellness journey overview
- **Customizable Settings**: Name, language, themes, and accessibility options
- **Wellness Goals**: Set and track personal mental health objectives
- **Statistics Tracking**: Real-time metrics and progress visualization
- **Activity History**: Detailed log of assessments and achievements
- **Streak Monitoring**: Daily engagement rewards and consistency tracking

### 🎨 Modern UI/UX Design
- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Dark/Light Mode**: System-aware theme switching
- **Glass Morphism**: Modern translucent design elements
- **Smooth Animations**: Framer Motion powered transitions
- **Accessibility Features**: High contrast mode and keyboard navigation
- **Toast Notifications**: Real-time feedback and success messages

### 🚀 Onboarding Experience
- **3-Step Guided Tour**: Interactive introduction to platform features
- **Skip Functionality**: Jump directly to main application
- **Progressive Disclosure**: Learn features at your own pace
- **Visual Demonstrations**: Rich graphics and animations
- **Welcome Personalization**: Tailored experience setup

## 🚀 Technology Stack

### Frontend
- **React 18** - Modern component architecture with hooks
- **TypeScript** - Type-safe development and better IDE support
- **Tailwind CSS** - Utility-first styling with custom design system
- **Framer Motion** - Smooth animations and micro-interactions
- **Zustand** - Lightweight state management with persistence

### AI & External Services
- **Google Gemini Pro** - Advanced AI language model for insights
- **Google Translate API** - Multi-language support for global users

### Blockchain & Web3
- **Ethers.js** - Ethereum wallet integration and smart contracts
- **Base Sepolia** - Layer 2 testnet for cost-effective transactions
- **MetaMask** - Secure wallet connection and authentication

### Additional Libraries
- **react-beautiful-dnd** - Drag and drop functionality for assessments
- **react-hot-toast** - Beautiful toast notifications
- **Lucide React** - Modern icon system with 1000+ icons
- **Recharts** - Data visualization for progress tracking
- **React Router** - Client-side routing and navigation

## 🛠️ Installation & Setup

### Prerequisites
- Node.js 18+ and npm/yarn
- MetaMask browser extension
- Google Gemini API key

### 1. Clone the Repository
```bash
git clone https://github.com/arpit15006/MindFulChain-AI-Powered-Mental-Wellness.git
cd mindfulchain
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Environment Configuration
Create a `.env.local` file in the root directory:
```env
VITE_GEMINI_API_KEY=your_google_gemini_api_key_here
```

### 4. Start Development Server
```bash
npm run dev
```

Visit `http://localhost:8080` to see the application.

## 🎯 Usage Guide

### Getting Started
1. **Welcome Onboarding**: Complete the 3-step guided introduction
2. **Connect Wallet**: Link your MetaMask for blockchain features
3. **Take Assessment**: Start with the interactive mood evaluation
4. **Receive AI Feedback**: Get personalized insights from Google Gemini
5. **Play Games**: Engage with cognitive training activities
6. **Earn Rewards**: Collect MINDFUL tokens and achievement NFTs
7. **Track Progress**: Monitor your wellness journey over time
8. **Chat with AI**: Access 24/7 mental health support

### Assessment Process
- **Drag & Drop Interface**: Move emotion cards to frequency buckets
- **5 Categories**: Evaluate mood, sleep, stress, focus, and energy
- **Progress Tracking**: See completion status with visual indicators
- **Reset Anytime**: Start fresh with complete state reset
- **Instant Feedback**: Receive AI insights upon completion

### Wallet Setup
- Install MetaMask browser extension
- Add Base Sepolia testnet (automatic prompt)
- Get test ETH from Base Sepolia faucet if needed
- Connect to earn and collect blockchain rewards

## 🏗️ Architecture

### Component Structure
```
src/
├── components/
│   ├── Layout.tsx              # Main app layout with navigation
│   ├── HomePage.tsx            # Landing page with features
│   ├── OnboardingPage.tsx      # 3-step guided introduction
│   ├── QuizPage.tsx            # Interactive assessment interface
│   ├── DashboardPage.tsx       # Analytics and progress tracking
│   ├── ProfilePage.tsx         # User settings and statistics
│   ├── ChatBotPage.tsx         # AI therapist chat interface
│   ├── GamesPage.tsx           # Wellness games collection
│   ├── NFTGallery.tsx          # Blockchain rewards showcase
│   └── games/
│       ├── MemoryGame.tsx      # Pattern recognition game
│       ├── ReactionTimeGame.tsx # Speed testing game
│       ├── MathLightningGame.tsx # Arithmetic challenges
│       └── BreathingExercise.tsx # Meditation guide
├── services/
│   ├── geminiService.ts        # AI integration and prompts
│   ├── nftService.ts           # Blockchain NFT management
│   ├── blockchainService.ts    # Web3 wallet connections
│   └── localStorageService.ts  # Data persistence
├── stores/
│   └── mindfulStore.ts         # Global state management
└── data/
    └── emotionCards.ts         # Assessment content and categories
```

### State Management
- **Zustand Store** - Global application state with persistence
- **Local Storage** - User preferences and progress backup
- **React Context** - Theme and UI state management
- **Component State** - Temporary UI interactions

## 🎨 Design System

### Color Palette
- **Primary**: Mindful Blue (#0ea5e9) - Trust and stability
- **Secondary**: Wellness Green (#22c55e) - Growth and healing
- **Accent**: Purple Gradient (#667eea → #764ba2) - Innovation
- **Background**: Soft gradients with glass morphism effects

### Typography
- **Font Family**: Inter (Google Fonts) - Modern and readable
- **Hierarchy**: Clear visual hierarchy with gradient text effects
- **Responsive**: Fluid typography scaling across devices
- **Accessibility**: High contrast ratios and proper sizing

### Animations
- **Framer Motion** - Page transitions and component animations
- **CSS Animations** - Floating elements and gradient effects
- **Hover Effects** - Scale, glow, and color transitions
- **Loading States** - Smooth loading indicators and skeletons

## 🔐 Security & Privacy

### Data Protection
- **Client-Side Processing** - All assessments processed locally
- **Encrypted Storage** - Sensitive data protection
- **Blockchain Verification** - Tamper-proof achievement records
- **No Personal Data Collection** - Privacy-first approach

### Smart Contract Security- A unique feature 
- **Audited Contracts** - ERC-20 and ERC-1155 standard compliance
- **Testnet Deployment** - Safe testing environment
- **Minimal Permissions** - Limited contract interactions
- **Secure Wallet Integration** - MetaMask security standards

## 🌍 Global Impact & Accessibility

### Mental Health Statistics
- **1 billion people** affected by mental health disorders worldwide (WHO)
- **Every 40 seconds** someone dies by suicide globally
- **$1 trillion** annual economic impact of depression and anxiety

### Our Solution
- **Accessibility Features** - High contrast, keyboard navigation, screen reader support
- **Multi-language Support** - AI-powered translation for global reach
- **Gamification** - Increase engagement through rewards and achievements
- **24/7 AI Support** - Provide round-the-clock mental health guidance
- **Blockchain Incentives** - Motivate consistent wellness tracking

## 🔮 Future Roadmap

### Phase 1 (Completed ✅)
- ✅ Core gamified assessment system
- ✅ AI-powered feedback with Google Gemini
- ✅ Blockchain integration with NFT rewards
- ✅ Beautiful responsive UI/UX design
- ✅ Wellness games and cognitive training
- ✅ AI therapist chat functionality
- ✅ Comprehensive user profiles
- ✅ Onboarding experience

### Phase 2 (In Progress 🔄)
- 🔄 Advanced analytics dashboard
- 🔄 Social features and community building
- 🔄 Therapist connection platform
- 🔄 Mobile app development
- 🔄 Integration with wearable devices

### Phase 3 (Future 📋)
- 📋 Clinical partnerships and validation
- 📋 Insurance integration and coverage
- 📋 Research data contribution
- 📋 Global scaling and localization
- 📋 Enterprise wellness programs

### Areas for Contribution
- **Frontend Development** - React, TypeScript, Tailwind CSS
- **AI Integration** - Prompt optimization, model fine-tuning
- **Blockchain Development** - Smart contracts, Web3 integration
- **UI/UX Design** - Accessibility, user experience improvements
- **Mental Health Content** - Assessment questions, wellness tips
- **Testing** - Unit tests, integration tests, user testing

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini** for advanced AI capabilities and natural language understanding
- **Base Protocol** for scalable blockchain infrastructure and developer tools
- **Mental Health Organizations** worldwide for research and inspiration
- **Open Source Community** for amazing tools, libraries, and frameworks
- **Contributors** who help improve mental wellness accessibility

## 📞 Support & Contact

- **Website**: [MindfulChain](https://mind-ful-chain-ai.vercel.app/)
- **Email**: arpi6814@gmail.com
- **GitHub**: [Report issues and contribute](https://github.com/arpit15006/MindFulChain-AI-Powered-Mental-Wellness.git)

---

<div align="center">
  <p><strong>Built with ❤️ for global mental wellness</strong></p>
  <p>Made for AlgoArena Hackathon 2025</p>
  <p><em>Together, we're building a healthier digital world</em></p>
</div>
