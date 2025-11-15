# 🎓 CTFL Quiz App - Gamified Exam Preparation

A comprehensive, gamified web application for CTFL (Certified Tester Foundation Level) exam preparation. Features an RPG-style progression system, achievements, daily challenges, and interactive learning tools to make studying engaging and effective.

![CTFL Quiz App](https://img.shields.io/badge/CTFL-Exam%20Prep-blue)
![React](https://img.shields.io/badge/React-18-61dafb)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

### 🎮 Core Quiz System
- **50 CTFL Questions** across 6 chapters covering all exam topics
- **Multiple Quiz Modes**: All topics, chapter-specific, or timed exam simulation
- **K-Level Classification**: Questions categorized by Bloom's taxonomy (K1, K2, K3)
- **Instant Feedback**: Detailed explanations for every answer
- **Chapter Performance Tracking**: Monitor accuracy by chapter

### 🏆 RPG Progression System
- **30 Levels** with exponential XP requirements
- **Title System**: Earn titles from "Test Novice" to "Test Architect"
- **XP Rewards**: Different XP for K1 (10 XP), K2 (15 XP), K3 (20 XP) questions
- **Level-Up Animations**: Confetti celebrations and bonus token rewards
- **Progress Bar**: Real-time XP tracking with visual feedback

### 🥇 Competitive Ranking System
- **5 Rank Tiers**: Bronze → Silver → Gold → Platinum → Diamond
- **Rank Badges**: Display your current rank (Apprentice, Skilled, Expert, Master, Elite Tester)
- **Progress Tracking**: See exactly how much XP needed for next rank
- **Personal Leaderboard**: Top 10 study sessions ranked by performance
- **Weekly Challenge**: Earn 2000 XP per week for 500 bonus tokens

### 🏅 Achievement System
- **20 Achievements** across 4 categories:
  - **Progress**: Getting Started, Committed, Dedicated
  - **Chapter Mastery**: 90%+ accuracy per chapter (6 achievements)
  - **Skill-Based**: Perfectionist, Speed Demon, K3 Killer, Full Stack Tester
  - **Fun**: Early Bird, Night Owl, Weekend Warrior, Century Club
- **Achievement Tracking**: Progress indicators for each achievement
- **Toast Notifications**: Celebratory popups when unlocked

### 🔥 Daily Engagement
- **Daily Streak System**: Track consecutive study days
- **Milestone Rewards**: Bonus XP for 7, 30, 100-day streaks
- **4 Daily Missions** (resets at midnight):
  - Answer 10 questions (50 tokens)
  - Get 5 correct in a row (100 tokens)
  - Study for 15 minutes (75 tokens)
  - Complete a chapter quiz (150 tokens)
- **Bonus Completion**: +200 tokens + 1 power-up for all 4 missions

### 🎯 Timed Exam Mode
- **40 Questions**: Proportionally distributed across chapters (mirrors real exam)
- **60-Minute Timer**: Big, visible countdown with red warning (<10 min)
- **No Feedback**: Answer selection without seeing correct/wrong until completion
- **No Going Back**: Forward-only navigation
- **Auto-Submit**: Exam submitted when timer reaches zero
- **Comprehensive Results**: Pass/fail status, chapter breakdown, XP rewards (double XP for passing)
- **Exam History**: Track last 5 exam attempts with scores and times

### 💰 Token Economy & Power-Ups
- **Earn Tokens**: 10 tokens per correct answer, mission rewards, streak bonuses
- **Power-Up Shop**:
  - **50/50 Hint** (50 tokens): Eliminate 2 wrong answers
  - **Extra Time** (100 tokens): +30 seconds (exam mode only)
  - **Double XP** (200 tokens): 2x XP for next 5 questions
- **Inventory System**: Track owned power-ups and active effects

### 📊 Statistics Dashboard
- **Overview Cards**: Total questions, accuracy %, streak, XP, achievements
- **Performance Charts** (Chart.js):
  - Bar chart: Accuracy by chapter
  - Pie chart: Questions by K-level distribution
- **Detailed Breakdown**: Chapter-by-chapter stats table
- **Recent Exam History**: View past exam performances
- **Weak Areas Alert**: Red banner for chapters <70% accuracy

### 🗂️ Learning Tools
- **Flashcard Mode**: 23 flashcards across 5 categories
  - 7 Testing Principles
  - 4 Test Levels
  - 6 Test Types
  - 2 Static vs Dynamic
  - 4 BVA/EP Formulas
- **Quick Reference Guides**: One-page cheat sheets for all 6 chapters
- **Formula Helper**:
  - Interactive BVA calculator (2-value and 3-value approaches)
  - Interactive EP calculator
  - 3 example problems with solutions
- **Exam Tips Page**:
  - 8 common exam traps
  - 8 time management strategies
  - Memorize vs. Understand comparisons
  - Key formulas reference

### 📤 Export & Sharing
- **PDF Progress Report**: Comprehensive study report with stats, achievements, exam history
- **JSON Backup**: Download complete data backup
- **Import/Restore**: Load backup from JSON file (transfer between devices)
- **Friend Code System**: Share encoded progress stats with friends
- **Shareable Achievement Card**: Generate PNG image for social media
- **Print-Friendly**: Print reference guides, stats, and exam tips

### 🎨 UI/UX Features
- **Dark Mode**: Toggle between light and dark themes
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Smooth Animations**: CSS transitions for all interactions
- **Progress Indicators**: Visual feedback for all tracked metrics
- **Toast Notifications**: Non-intrusive achievement unlocks
- **Confetti Effects**: Celebrations for level-ups and milestones

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser!

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/gamified_CTFL_Exam_Prep_Game.git
cd gamified_CTFL_Exam_Prep_Game
```

2. **Open the app**:
Simply open `index.html` in your web browser:
```bash
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

Or use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Then open http://localhost:8000 in your browser
```

### No Build Required!
This is a single-file application using CDN-hosted libraries. No npm install, no build step - just open and play!

## 📖 How to Use

### Starting Your Journey

1. **Home Screen**: View your current level, XP, streak, and rank badge
2. **Choose a Mode**:
   - **Exam Mode**: 40-question timed simulation
   - **All Topics**: Random 40 questions from all chapters
   - **Chapter Quiz**: Focus on specific chapters
3. **Answer Questions**: Select your answer and view explanations
4. **Earn Rewards**: Gain XP, tokens, and unlock achievements
5. **Track Progress**: Visit Stats and Leaderboard pages

### Daily Routine

1. **Check Daily Missions**: Complete 4 missions for bonus rewards
2. **Maintain Streak**: Study daily to build your streak
3. **Use Power-Ups**: Spend tokens strategically on hints and boosts
4. **Review Stats**: Identify weak areas and focus study efforts
5. **Complete Weekly Challenge**: Earn 2000 XP for 500 bonus tokens

### Study Resources

- **Flashcards**: Review key concepts before quizzing
- **Quick Reference**: Print chapter cheat sheets
- **Formula Helper**: Practice BVA and EP calculations
- **Exam Tips**: Read strategies before taking practice exams

### Tracking Progress

- **Leaderboard**: View your top 10 study sessions
- **Stats Dashboard**: Analyze performance by chapter
- **Achievements**: Track and unlock all 20 achievements
- **Export Reports**: Generate PDF progress reports

## 🛠️ Technologies Used

### Frontend
- **React 18**: UI components and state management
- **Babel Standalone**: JSX transformation in-browser
- **Tailwind CSS**: Utility-first styling

### Libraries
- **Chart.js 4.4.0**: Performance charts and visualizations
- **canvas-confetti 1.6.0**: Celebration animations
- **Howler.js 2.2.3**: Audio support (optional)
- **html2canvas 1.4.1**: Screenshot generation for sharing
- **jsPDF 2.5.1**: PDF report generation

### Storage
- **localStorage**: All data persisted locally in browser
- **No backend required**: 100% client-side application

## 📚 Game Mechanics

### XP System
- **K1 Questions**: 10 XP
- **K2 Questions**: 15 XP
- **K3 Questions**: 20 XP
- **Double XP Power-Up**: 2x for next 5 questions
- **Exam Pass Bonus**: Double XP rewards

### Level Progression
- Level 1-5: 100 XP per level
- Level 6-10: 200 XP per level
- Level 11-20: 300 XP per level
- Level 21-30: 500 XP per level

### Rank Tiers (Total XP)
- **Bronze** (0-999): Apprentice Tester 🥉
- **Silver** (1000-2499): Skilled Tester 🥈
- **Gold** (2500-4999): Expert Tester 🥇
- **Platinum** (5000-9999): Master Tester 💎
- **Diamond** (10000+): Elite Tester 👑

### Token Economy
- Correct answer: 10 tokens
- Daily mission rewards: 50-150 tokens
- All missions bonus: 200 tokens
- Level up bonus: 100 tokens
- Weekly challenge: 500 tokens

## 🎯 Exam Coverage

### Chapter Distribution
1. **Chapter 1**: Fundamentals of Testing (8 questions)
2. **Chapter 2**: Testing Throughout SDLC (8 questions)
3. **Chapter 3**: Static Testing (8 questions)
4. **Chapter 4**: Test Design Techniques (10 questions)
5. **Chapter 5**: Test Management (8 questions)
6. **Chapter 6**: Tool Support (8 questions)

**Total**: 50 practice questions

### Exam Mode Distribution
Mirrors the real CTFL exam structure:
- Chapters 1-3: 6 questions each (18 total)
- Chapters 4-5: 8 questions each (16 total)
- Chapter 6: 6 questions
- **Total**: 40 questions in 60 minutes

## 💾 Data Management

### Local Storage Keys
- `ctfl-chapter-stats`: Chapter performance data
- `ctfl-rpg-progress`: XP and level
- `ctfl-streak-data`: Daily streak information
- `ctfl-achievements`: Unlocked achievements
- `ctfl-tokens`: Token balance
- `ctfl-inventory`: Power-up inventory
- `ctfl-exam-history`: Past exam results
- `ctfl-daily-missions`: Mission progress
- `ctfl-weekly-challenge`: Weekly challenge data
- `ctfl-study-sessions`: Leaderboard sessions
- `ctfl-settings`: App settings (dark mode, etc.)

### Export/Import
- Export all data as JSON backup
- Import from JSON to restore progress
- Transfer between devices easily
- No data loss when clearing browser cache (if backed up)

## 🎓 Learning Approach

This app uses evidence-based learning techniques:

1. **Spaced Repetition**: Daily missions encourage consistent practice
2. **Active Recall**: Question-based learning with immediate feedback
3. **Interleaving**: Mix of different chapters and K-levels
4. **Progress Tracking**: Visual feedback motivates continued learning
5. **Gamification**: Rewards system increases engagement
6. **Self-Assessment**: Stats dashboard highlights weak areas
7. **Variety**: Multiple learning modes (quiz, flashcards, reference guides)

## 🤝 Contributing

Contributions are welcome! Here are some ways to contribute:

1. **Add More Questions**: Expand the question bank
2. **Improve Explanations**: Enhance answer explanations
3. **Add Features**: New learning tools or game mechanics
4. **Fix Bugs**: Report and fix issues
5. **Improve UI/UX**: Design enhancements
6. **Localization**: Translations to other languages

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **ISTQB**: For the CTFL syllabus and certification program
- **React Team**: For the excellent framework
- **Tailwind CSS**: For the utility-first CSS framework
- **Chart.js**: For beautiful data visualizations
- **Community**: For feedback and suggestions

## 📧 Contact & Support

- **Issues**: Report bugs via GitHub Issues
- **Questions**: Open a discussion on GitHub
- **Feature Requests**: Submit via GitHub Issues with "enhancement" label

## 🗺️ Roadmap

### Planned Features
- [ ] Additional question banks (Advanced Level, Agile Tester)
- [ ] Multiplayer mode (compete with friends in real-time)
- [ ] AI-powered personalized study plans
- [ ] Video explanations for complex topics
- [ ] Mobile app versions (iOS/Android)
- [ ] Cloud sync for multi-device progress
- [ ] Community-contributed questions
- [ ] Practice exam certification

## 📊 Stats at a Glance

- **50** practice questions
- **6** chapters covered
- **20** achievements to unlock
- **30** levels to progress through
- **5** rank tiers
- **4** daily missions
- **3** power-up types
- **23** flashcards
- **100%** fun and engaging!

---

**Start your CTFL journey today and ace that certification exam!** 🎉

Made with ❤️ for aspiring testers worldwide.
