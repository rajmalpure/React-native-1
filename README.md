# ✨ My Todo App

A beautiful, modern Todo application built with React Native and Expo. Stay organized and boost your productivity with this intuitive task management app!

![Todo App](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-blue?style=for-the-badge)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

## 🚀 Live Demo

### Try it now on your phone!

**📱 Expo Go (Recommended)**
- Download "Expo Go" app from your phone's app store
- Visit the link:

**🔗 Live App Link:** [https://expo.dev/accounts/rajmalpure/projects/MyTodoApp](https://expo.dev/accounts/rajmalpure/projects/MyTodoApp)

**📊 Project Dashboard:** [View on EAS Dashboard](https://expo.dev/accounts/rajmalpure/projects/MyTodoApp/updates/00e3d6f4-b761-4219-a6f1-dfc1d45609b7)

---

## 📱 Screenshots

| Home Screen | Add Tasks | Task Management |
|-------------|-----------|-----------------|
| 📋 Clean interface | ➕ Easy task creation | ✅ Mark complete & delete |

## ✨ Features

### Core Functionality
- ✅ **Add Tasks** - Quickly add new tasks with a simple interface
- ✅ **Mark Complete** - Tap the circle to mark tasks as done
- ✅ **Delete Tasks** - Remove tasks with confirmation dialog
- ✅ **Task Statistics** - See total, completed, and pending tasks at a glance
- ✅ **Clear Completed** - Bulk remove all completed tasks

### User Experience
- 🎨 **Modern Design** - Beautiful, clean interface with smooth animations
- 📱 **Cross-Platform** - Works on both iOS and Android
- ⚡ **Live Reload** - Instant updates during development
- 🔄 **Real-time Updates** - Changes sync immediately across devices
- 📅 **Task Timestamps** - See when each task was created

### Technical Features
- 🚀 **Fast Performance** - Built with React Native for native performance
- 💾 **State Management** - Efficient in-memory task storage
- 📱 **Responsive Design** - Adapts to different screen sizes
- 🔒 **Safe Operations** - Confirmation dialogs for destructive actions

---

## 🛠️ Technology Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| **React Native** | Mobile app framework | Latest |
| **Expo** | Development platform | SDK 53.0.0 |
| **JavaScript** | Programming language | ES6+ |
| **React Hooks** | State management | useState |
| **EAS Update** | Over-the-air updates | Latest |

---

## 📥 Installation & Setup

### Prerequisites
- **Node.js** (v14 or later)
- **npm** or **yarn**
- **Expo Go** app on your phone

### Quick Start
```bash
# Clone the repository
git clone https://github.com/rajmalpure/MyTodoApp.git

# Navigate to project directory
cd MyTodoApp

# Install dependencies
npm install

# Start the development server
expo start
```

### Development Setup
```bash
# Install Expo CLI globally
npm install -g expo-cli

# Install EAS CLI for builds and updates
npm install -g @expo/eas-cli

# Login to your Expo account
expo login

# Start development
expo start
```

---

## 🚀 Deployment

This app is deployed using **Expo EAS (Expo Application Services)**.

### Current Deployment Status
- **Status:** ✅ Live and Running
- **Platform:** iOS & Android
- **Runtime Version:** 1.0.0
- **Last Updated:** Recently deployed
- **Update ID:** `00e3d6f4-b761-4219-a6f1-dfc1d45609b7`

### Deployment Commands Used
```bash
# Configure EAS updates
eas update:configure

# Deploy new version
eas update --branch production --message "My Todo App"
```

### Build for App Stores
```bash
# Build for Android (Google Play Store)
eas build --platform android

# Build for iOS (Apple App Store)
eas build --platform ios

# Build for both platforms
eas build --platform all
```

---

## 📖 How to Use

### Adding Tasks
1. Open the app
2. Type your task in the input field
3. Tap "Add" or press Enter
4. Your task appears at the top of the list

### Managing Tasks
- **Mark Complete:** Tap the circle next to any task
- **Delete Task:** Tap the 🗑️ trash icon
- **View Stats:** Check the statistics bar for your progress

### Bulk Actions
- **Clear Completed:** Use the red button to remove all completed tasks
- **Track Progress:** Monitor your productivity with real-time statistics

---

## 🏗️ Project Structure

```
MyTodoApp/
├── App.js                 # Main app component
├── app.json              # Expo configuration
├── package.json          # Dependencies and scripts
├── babel.config.js       # Babel configuration
├── metro.config.js       # Metro bundler configuration
├── eas.json             # EAS configuration
└── assets/              # App icons and splash screens
    ├── icon.png
    ├── splash.png
    └── adaptive-icon.png
```

---

## 🎨 Design Philosophy

### Color Palette
- **Primary:** `#6366f1` (Indigo) - Header and primary actions
- **Success:** `#10b981` (Emerald) - Completed tasks and add button
- **Warning:** `#f59e0b` (Amber) - Pending tasks counter
- **Danger:** `#ef4444` (Red) - Delete actions
- **Background:** `#f8fafc` (Slate) - App background
- **Surface:** `#ffffff` (White) - Cards and inputs

### Typography
- **Headers:** Bold, large text for important information
- **Body:** Clean, readable font for task content
- **Captions:** Smaller text for timestamps and metadata

### User Interface
- **Cards:** Rounded corners with subtle shadows
- **Buttons:** Colorful with proper touch feedback
- **Spacing:** Consistent margins and padding throughout
- **Animation:** Smooth transitions and interactions

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Getting Started
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Commit your changes: `git commit -m 'Add amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Development Guidelines
- Follow React Native best practices
- Write clean, commented code
- Test your changes on both iOS and Android
- Update documentation for new features

---

## 📝 Roadmap

### Version 2.0 (Planned)
- [ ] **Data Persistence** - Save tasks locally with AsyncStorage
- [ ] **Categories** - Organize tasks by categories
- [ ] **Due Dates** - Set deadlines for tasks
- [ ] **Priority Levels** - High, medium, low priority tasks
- [ ] **Dark Mode** - Toggle between light and dark themes

### Version 3.0 (Future)
- [ ] **Cloud Sync** - Sync tasks across devices
- [ ] **Notifications** - Reminders for important tasks
- [ ] **Collaboration** - Share task lists with others
- [ ] **Analytics** - Productivity insights and reports
- [ ] **Voice Input** - Add tasks using voice commands

---

## 🐛 Known Issues

Currently, there are no known critical issues. If you encounter any problems:

1. **App won't load:** Make sure you have the latest Expo Go app
2. **QR code won't scan:** Ensure your phone and computer are on the same network
3. **Tasks not saving:** This version uses in-memory storage (tasks reset on app restart)

---

## ❓ FAQ

### Q: Do I need to pay anything to use this app?
A: No! The app is completely free to use and open source.

### Q: Will my tasks be saved if I close the app?
A: Currently, tasks are stored in memory and will be lost when you close the app. Data persistence is planned for v2.0.

### Q: Can I use this app offline?
A: Yes! Once loaded, the app works completely offline.

### Q: How do I get the latest updates?
A: Updates are delivered automatically through Expo. Just restart the app to get the latest version.

### Q: Can I contribute to this project?
A: Absolutely! Check the Contributing section above for guidelines.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Raj Malpure

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 👨‍💻 Author

**Raj Malpure**
- GitHub: [@rajmalpure](https://github.com/rajmalpure)
- Expo: [@rajmalpure](https://expo.dev/@rajmalpure)

---

## 🙏 Acknowledgments

- **React Native Community** - For the amazing framework
- **Expo Team** - For making mobile development accessible
- **Contributors** - Everyone who helps improve this project
- **Users** - Thank you for using and testing the app!

---

## 📞 Support

Need help? Have questions?

- **GitHub Issues:** [Create an issue](https://github.com/rajmalpure/MyTodoApp/issues)
- **Expo Community:** [Expo Forums](https://forums.expo.dev/)
- **Documentation:** [React Native Docs](https://reactnative.dev/)

---

## 🎯 Why This Project?

This Todo app was created as:
- **Learning Project** - Perfect for React Native beginners
- **Portfolio Piece** - Demonstrates mobile development skills
- **Open Source Contribution** - Helping others learn mobile development
- **Real-World Application** - Actually useful for daily productivity

---

## 🌟 Show Your Support

If you found this project helpful:
- ⭐ Star this repository
- 🍴 Fork it for your own projects
- 📱 Try the live app
- 🐛 Report bugs or suggest features
- 💡 Contribute improvements

---

*Built with ❤️ using React Native and Expo*

**Happy Coding! 🚀**
