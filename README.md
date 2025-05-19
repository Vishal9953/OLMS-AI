# Educa Mobile App

A React Native mobile application for an educational platform built with Expo.

## Features

- **Modern UI**: Clean and responsive design with light/dark theme support
- **Course Browsing**: Browse and search through available courses
- **Course Details**: View detailed information about courses including descriptions, tutors, and content
- **Video Playlists**: Access course videos organized in playlists
- **Teacher Profiles**: View information about course instructors
- **Bookmarks**: Save courses for later viewing
- **Authentication**: Login and registration system (demo mode)
- **Theme Toggle**: Switch between light and dark themes

## Demo Features

This is an MVP version with the following simulated backend features:
- Authentication (login/registration)
- Course bookmarking
- Course and video data
- Theme persistence

## Prerequisites

- Node.js (v14+)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- iOS Simulator (macOS) or Android Emulator / physical device

## Installation

1. Clone this repository
```
git clone https://github.com/yourusername/educa-mobile.git
cd educa-mobile
```

2. Install dependencies
```
npm install
```

3. Start the development server
```
npm start
```

4. Open the app in your simulator or device:
   - iOS: Press `i` in the terminal or open in Xcode
   - Android: Press `a` in the terminal or open in Android Studio
   - Web: Press `w` in the terminal

## Project Structure

```
educaMobile/
├── src/
│   ├── components/       # Reusable UI components
│   ├── screens/          # Application screens
│   ├── navigation/       # Navigation configuration
│   ├── constants/        # Colors, themes, etc.
│   ├── utils/            # Utility functions
│   ├── hooks/            # Custom React hooks
│   └── assets/           # Images, fonts, etc.
├── App.js                # Main application component
└── package.json          # Dependencies and scripts
```

## Key Screens

- **Home**: Featured courses and teachers
- **Course List**: Browse and search all courses
- **Course Detail**: Course information and video playlist
- **Watch Video**: Video player with comments and likes
- **Teacher Profile**: Information about course instructors
- **Authentication**: Login and registration screens
- **Profile**: User profile management
- **Bookmarks**: User's saved courses

## Technology Stack

- **React Native**: Mobile app framework
- **Expo**: Development platform
- **React Navigation**: Navigation library
- **AsyncStorage**: Local storage solution

## Backend Integration

This MVP version uses mock data for demonstration purposes. To connect with a real backend:

1. Replace the mock data functions in `src/utils/themeUtils.js` with actual API calls
2. Implement proper authentication flow in login/register screens
3. Connect bookmarking and likes functionality to actual API endpoints

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Design inspired by the Educa educational platform
- Icons from [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
- Placeholder images from [Placeholder.com](https://placeholder.com)
