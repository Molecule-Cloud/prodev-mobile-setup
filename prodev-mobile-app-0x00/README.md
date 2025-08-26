# Mobile Development with React Native, TypeScript & Expo

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

## 📱 Project Overview

This repository contains a comprehensive mobile development setup using React Native, TypeScript, NativeWindCSS, and the Expo framework. This powerful stack enables cross-platform mobile application development with a single codebase for both iOS and Android platforms.

## 🚀 Technology Stack

- **React Native**: Open-source framework for building cross-platform mobile applications
- **TypeScript**: Strongly typed superset of JavaScript for enhanced development experience
- **NativeWindCSS**: Utility-first CSS framework tailored for React Native styling
- **Expo Framework**: Platform that simplifies React Native development and deployment

## ✨ Key Benefits

- **Cross-platform Development**: Write once, deploy on both iOS and Android
- **Type Safety**: TypeScript ensures fewer runtime errors and better code quality
- **Efficient Styling**: Utility-first CSS approach with NativeWindCSS
- **Rapid Development**: Expo's comprehensive toolset accelerates the development process
- **Hot Reloading**: Instant feedback during development with Expo Go

## 🛠️ Prerequisites

Before getting started, ensure you have the following installed:

- **Node.js** (v16 or higher)
- **VS Code** (recommended IDE)
- **Compatible OS**: macOS, Linux, or Windows
- **Expo Go** app on your mobile device (iOS/Android)

## 📦 Installation & Setup

### 1. Environment Setup

Install Expo CLI globally:

```bash
npm install -g expo-cli
```

### 2. Install Expo Go

1. Visit [Expo Go Homepage](https://expo.dev/go)
2. Select the latest SDK version
3. Install on your device:
   - **Android**: [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - **iOS**: [Apple App Store](https://apps.apple.com/app/expo-go/id982107779)

### 3. Project Initialization

Navigate to your project directory and create a new Expo project:

```bash
# Navigate to project directory
cd prodev-mobile-setup

# Create new Expo project with latest router template
npx create-expo-app@latest .

# Start development server
npx expo start
```

### 4. Testing on Device

- **iOS**: Scan QR code with Camera app
- **Android**: Scan QR code with Expo Go app

## 📂 Project Structure

```
prodev-mobile-setup/
├── mobile-development-setup/
├── prodev-mobile-app-0x00/
│   ├── app-example/
│   │   ├── app/(tabs)/index.tsx
│   │   └── constants/Colors.tsx
│   └── README.md
├── prodev-mobile-app-0x01/
│   └── app/index.tsx
├── prodev-mobile-app-0x02/
│   └── app/index.tsx
└── prodev-mobile-app-0x03/
    ├── app/
    │   ├── _layout.tsx
    │   └── index.tsx
    ├── assets/images/
    ├── styles/index.tsx
    └── README.md
```

## 🎯 Learning Objectives

This project progression covers:

### Task 0: Environment Setup
- Expo Go installation and configuration
- Development environment verification
- Device testing setup

### Task 1: First Mobile App
- Project scaffolding with Expo Router
- Understanding React Native file structure
- Basic component modification and testing

### Task 2: Core Components & Styling
- React Native component fundamentals (`View`, `Text`)
- StyleSheet implementation and best practices
- Cross-platform styling techniques

### Task 3: Advanced Components
- SafeAreaView for device compatibility
- Image and ImageBackground components
- TouchableOpacity for user interactions
- Responsive design with Dimensions API

### Task 4: Comprehensive UI Development
- Form components and user input handling
- Icon integration with Expo Vector Icons
- Complex layouts and styling patterns
- Social media authentication UI components

## 🔧 Core Components Used

| Component | Purpose | Platform Support |
|-----------|---------|-------------------|
| `SafeAreaView` | Handles device notches and safe areas | iOS/Android |
| `View` | Container component (like `div` in web) | iOS/Android |
| `Text` | Text display component | iOS/Android |
| `TextInput` | User input field | iOS/Android |
| `TouchableOpacity` | Touchable wrapper with opacity feedback | iOS/Android |
| `Image` | Static image display | iOS/Android |
| `ImageBackground` | Background image container | iOS/Android |

## 📱 Sample Applications

### App 0x00: Basic Setup
- Environment verification
- Template exploration
- Development workflow establishment

### App 0x01: Styling Fundamentals
```typescript
// Example: Custom text styling
const styles = StyleSheet.create({
  largeText: {
    fontSize: 30,
    color: "#f44336",
    marginBottom: 5,
    fontWeight: "700",
    fontVariant: ["small-caps"],
  },
  // Additional styles...
});
```

### App 0x02: Interactive UI
- Background images and safe areas
- Interactive buttons and navigation
- Responsive design implementation

### App 0x03: Complete Login Screen
- Form handling and validation
- Social media integration UI
- Professional styling and layout

## 🎨 Styling Best Practices

1. **Use StyleSheet.create()** for performance optimization
2. **Implement responsive designs** using Dimensions API
3. **Consistent color schemes** across components
4. **Platform-specific styling** when necessary
5. **Accessibility considerations** for text sizing and contrast

## 🧪 Testing & Development

### Running the Application
```bash
# Start development server
npx expo start

# Reset project (removes template files)
npm run reset-project
```

### Testing on Physical Devices
- Use Expo Go for instant testing
- No need for complex emulator setup
- Cross-platform testing on actual hardware

## 🚨 Troubleshooting

### Common Issues

1. **QR Code Not Scanning**: Ensure both devices are on the same network
2. **Metro Bundler Errors**: Clear cache with `npx expo start -c`
3. **TypeScript Errors**: Check type definitions and imports
4. **Asset Loading Issues**: Verify file paths and asset locations

### Reset Project
```bash
npm run reset-project
```
This command removes template files and provides a clean starting point.

## 📈 Project Assessment

This is a hybrid assessment project evaluated through:

- ✅ Timely project completion
- 📄 All required files submission
- 🔗 Generated review links
- 👥 Peer review participation

**⚠️ Important**: Submit before deadline to generate review links!

## 📚 Additional Resources

- [React Native Documentation](https://reactnative.dev/)
- [Expo Documentation](https://docs.expo.dev/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [React Native Components](https://reactnative.dev/docs/components-and-apis)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is part of the ALX Professional Development program.

## 🎉 Acknowledgments

- Meta (Facebook) for React Native
- Expo team for the comprehensive development platform
- ALX for the structured learning approach

---

**Happy Coding!** 🚀✨

*Built with ❤️ using React Native, TypeScript, and Expo*