# DatingCoachGPT
DatingCoachGPT is a dating coach that uses AI to help you with any questions you have about dating. Be it how to ask someone out, how to make a good first impression, or how to keep the conversation going, DatingCoachGPT is here to help.

## Table of Contents
  - [Live Demo](#live-demo)
  - [Screenshots](#screenshots)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [How to use the application](#how-to-use-the-application)
  - [API Reference](#api-reference)
  - [Use Cases & Future Enhancements](#use-cases-and-future-enhancements)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [FAQ](#faq)

## Live Demo

[https://DatingCoachGPT.vercel.app](https://DatingCoachGPT.vercel.app)

## Features

- User Authentication and Profile Management
- AI-Powered Dating Advice and Coaching
- Personalized Conversation Strategies
- Dating Profile Review and Optimization
- Real-time Feedback on Dating Scenarios

## Technologies Used

- Next.js for Frontend and Backend
- Chakra UI for Responsive Design
- OpenAI GPT-4 Model for AI-Powered Features
- MongoDB for Database Management
- Json Web Token for Authentication

## Getting Started

### Prerequisites

- Node.js (version 14 or later)
- MongoDB 
- OpenAI API key

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/0xmetaschool/dating-coach-gpt
   cd dating-coach-gpt
   ```

2. Install dependencies:

   ```
   npm install
   ```

   This will install the following key dependencies:
   - next: React framework for production
   - react and react-dom: Core React libraries
   - @chakra-ui/react, @emotion/react, @emotion/styled, framer-motion: UI component library and its dependencies
   - axios: Promise-based HTTP client for making API requests
   - openai: OpenAI API client for Node.js
   - mongodb: MongoDB driver for Node.js
   - jsonwebtoken: JavaScript implementation of JSON Web Tokens
   - bcryptjs: Library for hashing passwords
   - react-icons: Icon library for React

3. Set up environment variables:
   - Create a `.env.local` file in the root directory
   - Add the following variables:
     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret  
     OPENAI_API_KEY=your_openai_api_key
     ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Screenshots

<div style="display: flex; justify-content: space-between;">
  <img src="screenshots/home.png" alt="Home Page" style="width: 49%; border: 2px solid black;" />
  <img src="screenshots/chat.png" alt="Matches Page" style="width: 49%; border: 2px solid black;" />
</div>

<div style="margin-top: 10px;">
  <img src="screenshots/messages.png" alt="Profile Page" style="width: 49%; border: 2px solid black;" />
</div>

## How to use the application

1. Getting Started with DatingCoachGPT:
   - Create a new account or sign in to your existing one
   - Complete your profile with accurate personal information
   - Add detailed descriptions of your interests, hobbies, and preferences

2. Maximizing Your Dating Success:
   - Use the app to get personalized advice on how to improve your dating game
   - Practice conversation scenarios with the app before real interactions
   - Get feedback on your dating profile and how to optimize it for better matches
   - Use the app to prepare for dates and improve your chances of success

## API Reference

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/auth/signup` | POST | Creates a new user account |
| `/api/auth/login` | POST | Logs in an existing user |
| `/api/profile` | POST | Updates user profile |
| `/api/matches` | GET | Retrieves potential matches |
| `/api/likes` | POST | Sends a like to another user |
| `/api/chat` | POST | Sends a message to a match |
| `/api/photos` | POST | Uploads profile photos |
| `/api/preferences` | PUT | Updates matching preferences |
| `/api/suggestions` | GET | Gets AI-powered conversation starters |
| `/api/block` | POST | Blocks a user |

Note: All endpoints except `/api/auth/signup` and `/api/auth/login` require authentication via a Bearer token in the Authorization header.

## Use Cases & Future Enhancements

**Current Use Cases:**
- Find potential matches based on compatibility
- Engage in meaningful conversations with AI assistance
- Share and view verified profile photos
- Set dating preferences and filters
- Report inappropriate behavior

**Coming Soon:**
- Video chat integration
- AI-powered date planning suggestions
- Virtual dating events
- Advanced matching algorithms
- Profile verification badges
- Location-based matching
- Integration with social media platforms

Want to contribute? Check out our contributing guidelines below!

## Contributing

We love contributions! Here's how you can help make the project even better:

- Fork the project (gh repo fork https://github.com/yourusername/date-match)
- Create your feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenAI for the GPT-4 API
- Chakra UI team for their React component library

## FAQ

**Q: Is DatingCoachGPT free to use?**
A: DatingCoachGPT offers both free and premium tiers. Basic matching and messaging are free, while advanced features require a subscription.

**Q: How does the AI matching work?**
A: Our AI analyzes profiles, interests, behavior patterns, and stated preferences to suggest compatible matches.

**Q: Is my data secure?**
A: Yes, we take data security and privacy very seriously. All user data is encrypted, and we never share your personal information with third parties.