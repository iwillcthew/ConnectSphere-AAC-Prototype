# ConnectSphere AAC

## Overview

ConnectSphere is a prototype Augmentative and Alternative Communication (AAC) application designed to help children with communication challenges express themselves more effectively. This repository contains a demonstration version showcasing the core features and user interfaces of the ConnectSphere system.

## ⚠️ Demo/Prototype Notice

**This is a non-functional prototype designed for demonstration purposes only.** The application simulates the user experience and interface of the ConnectSphere AAC system but does not include backend functionality or data persistence.

## Features

- **Communication Interface**: Symbol-based communication board with customizable layouts
- **Schedule Management**: Visual daily schedule with activity tracking
- **AI Image Generation**: Demo workflow showing how custom symbols can be created using AI
- **Guardian Hub**: Central access point for caregivers and educators to manage settings
- **Progress Reports**: Data visualization showing communication progress and patterns
- **AI-Powered Predictions**: Context-aware word suggestions based on previous selections
- **Smart Sentence Completion**: AI assistance to help complete sentences based on started phrases
- **Automated Reporting**: AI-generated insights and communication pattern analysis
- **Adaptive Learning**: System that learns from user's communication patterns and adapts accordingly

## Files Structure

- `home.html` - Main entry point and landing page
- `communication.html` - Main AAC communication interface
- `guardian-hub.html` - Administrative panel for parents/guardians
- `schedule.html` - Daily activity schedule visualization
- `reports-progress.html` - Communication progress tracking and reporting
- `ai-image-step1.html`, `ai-image-step2.html`, `ai-image-step3.html` - AI image creation workflow
- `connectsphere-documentation.txt` - Project documentation and notes
- `connectsphere-documentation.pdf` - Full project documentation (PDF format)

## Usage

This is a front-end only prototype. To explore the interface:

1. Clone the repository
2. Open `home.html` in a modern web browser
3. Navigate through the various screens using the UI buttons

## Design Principles

ConnectSphere was designed with the following core principles:

- **Accessibility**: Interfaces optimized for users with diverse abilities
- **Visual Clarity**: Clean, distraction-free design with consistent visual language
- **Progressive Learning**: System adapts to the user's communication development
- **Data-Informed Support**: Progress tracking to help caregivers provide targeted assistance

## Technologies Used

- HTML5
- CSS3
- JavaScript (vanilla)

## AI Features Demo

The prototype demonstrates several AI-powered capabilities that enhance communication:

### Context-Aware Predictions
- Suggests next words based on previous selections and common phrase patterns
- Offers category-specific vocabulary based on conversation context
- Adapts prediction priority based on frequently used word combinations

#### How Dynamic Word Suggestions Work
The system analyzes the words selected by the user and dynamically changes the suggestions in the following ways:

1. **Initial suggestions**: When no words are selected, the system shows common starting words like "I", "Want", "Eat"
2. **Single-word context**: After selecting a word like "I", suggestions change to show relevant follow-ups like "Want", "Need", "Like"
3. **Two-word combinations**: When patterns like "I want" are detected, suggestions become more specific like "Food", "Drink", "Help"
4. **Category awareness**: The system recognizes categories (e.g., Food or Animals) and suggests related vocabulary
5. **Visual feedback**: A subtle animation and label change helps users understand why suggestions are changing

Example flows:
- "I" → [Want, Like, Need, Feel...] → "I want" → [Food, Help, Play...] → "I want food" → [More, Drink, Please...]
- "Feel" → [Happy, Sad, Tired...] → "Feel happy" → [Because, When, Now...]

### Smart Sentence Completion
- Analyzes partial sentences to suggest appropriate completions
- Provides grammatically correct options to complete thoughts
- Learns from user choices to improve future suggestions

### Automated Reports & Insights
- Generates weekly communication summaries with key metrics
- Identifies patterns in symbol usage and communication contexts
- Suggests new vocabulary to introduce based on current mastery
- Highlights potential communication breakthroughs and milestones

## Future Development

In a full implementation, ConnectSphere would include:

- Backend database for storing user data and communication history
- Real AI integration for symbol generation
- Enhanced AI prediction with machine learning models
- Natural language processing for improved sentence construction
- Personalized vocabulary expansion based on usage patterns
- Real-time analysis of communication effectiveness
- Sentiment analysis to understand emotional context
- User authentication system
- Native mobile application versions
- API connections to educational resources
- Voice output for symbol selection
- Multi-language support
- Integration with smart home devices for environmental control

## License

This project is provided as a demonstration only and is not licensed for production use.

---

*Note: ConnectSphere is a prototype created for demonstration and educational purposes. The current implementation does not include actual data storage or processing capabilities.*
