# SwiftQuantum Learning App 🚀

An interactive iOS/macOS application for learning quantum computing concepts through gamified lessons, practice exercises, and visual demonstrations.

![Swift](https://img.shields.io/badge/Swift-5.9-orange)
![iOS](https://img.shields.io/badge/iOS-17.0+-blue)
![macOS](https://img.shields.io/badge/macOS-14.0+-purple)
![SwiftUI](https://img.shields.io/badge/SwiftUI-5.0-green)

## ✨ Features

### 📚 Learning System
- **Structured Learning Tracks**: Beginner, Intermediate, and Advanced paths
- **Interactive Lessons**: Theory, practice, and quiz sections
- **Progress Tracking**: XP system, level completion, and streak tracking
- **Gamification**: Achievements, badges, and rewards

### 🎮 Practice & Exploration
- **Quantum Gate Simulator**: Interactive gate operations on qubits
- **Superposition Lab**: Visualize quantum state superposition
- **Entanglement Demo**: Explore quantum entanglement concepts
- **Algorithm Examples**: Deutsch-Jozsa, Grover's search, and more

### 👤 User Features
- **Profile Management**: Track progress, achievements, and study time
- **Achievement System**: Unlock badges and earn XP
- **Daily Challenges**: Maintain learning streaks
- **Offline Support**: Learn without internet connection

### 🎨 Design
- **Dark Theme**: Quantum-inspired color scheme
- **Animated UI**: Smooth transitions and interactive elements
- **Cross-Platform**: Native iOS and macOS support
- **Accessibility**: VoiceOver support and dynamic type

## 🛠 Tech Stack

- **SwiftUI**: Modern declarative UI framework
- **Combine**: Reactive programming for data flow
- **MVVM Architecture**: Clean separation of concerns
- **Singleton Pattern**: Centralized service management

## 📱 Screenshots

| Home | Learn | Practice | Profile |
|------|-------|----------|---------|
| 🏠 Dashboard with progress overview | 📖 Structured learning paths | 🧪 Interactive quantum labs | 👤 Achievement tracking |

## 🚀 Getting Started

### Prerequisites
- Xcode 15.0 or later
- iOS 17.0+ / macOS 14.0+
- Swift 5.9+

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/SwiftQuantumLearning.git
cd SwiftQuantumLearning
```

2. Open in Xcode
```bash
open SwiftQuantumLearning.xcodeproj
```

3. Build and run
- Select target device (iPhone/iPad/Mac)
- Press `Cmd + R` to build and run

## 📁 Project Structure
```
SwiftQuantumLearning/
├── Models/
│   ├── Achievement.swift
│   ├── LearningLevel.swift
│   ├── PracticeItem.swift
│   ├── UserProgress.swift
│   └── QubitState.swift
├── ViewModels/
│   ├── HomeViewModel.swift
│   ├── LearnViewModel.swift
│   ├── PracticeViewModel.swift
│   ├── ExploreViewModel.swift
│   ├── ProfileViewModel.swift
│   ├── ProgressViewModel.swift
│   └── AchievementViewModel.swift
├── Views/
│   ├── Home/
│   ├── Learn/
│   ├── Practice/
│   ├── Explore/
│   └── Profile/
├── Services/
│   ├── LearningService.swift
│   ├── ProgressService.swift
│   ├── StorageService.swift
│   └── AchievementService.swift
├── Design/
│   ├── QuantumColors.swift
│   ├── QuantumTheme.swift
│   └── Components/
└── Resources/
```

## 🎯 Key Features Implementation

### Quantum State Visualization
```swift
// Qubit state representation
struct QubitState {
    var alpha: Complex
    var beta: Complex
    
    var prob0: Double {
        alpha.magnitude * alpha.magnitude
    }
}
```

### Achievement System
```swift
// Track user achievements
class AchievementService {
    func checkAndUnlockAchievements() {
        // XP-based achievements
        // Streak achievements
        // Level completion achievements
    }
}
```

### Learning Progress
```swift
// Comprehensive progress tracking
struct UserProgress {
    var totalXP: Int
    var completedLevels: Set<Int>
    var currentStreak: Int
    var achievements: [String]
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Inspired by quantum computing education platforms
- Built with SwiftUI and modern iOS development practices
- Special thanks to the quantum computing community

## 📧 Contact

Muna Park - [@eunminpark](https://github.com/eunmin-park)

Project Link: [https://github.com/yourusername/SwiftQuantumLearning](https://github.com/yourusername/SwiftQuantumLearning)

---
Made with ❤️ for quantum computing education
