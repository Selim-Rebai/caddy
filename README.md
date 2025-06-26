# 🛒 Caddy - Smart Shopping List App

A modern and intuitive Flutter mobile application for managing your shopping lists with advanced AI features and intelligent suggestions.

## ✨ Features

### 🎯 Core Features
- **Multi-list management**: Create and manage multiple shopping lists
- **Smart suggestions**: AI-powered recommendations based on your shopping habits
- **Auto-categorization**: Items organized by categories (Fruits & Vegetables, Meat, Dairy, etc.)
- **Complete history**: Browse and reuse your previous lists
- **Modern interface**: Material 3 design with smooth animations
- **Offline functionality**: Automatic cloud synchronization

### 🤖 Artificial Intelligence
- **Contextual suggestions**: Recommendations based on selected category
- **Adaptive learning**: AI learns from your shopping patterns
- **Auto-completion**: Real-time suggestions while typing
- **Smart categorization**: Automatic classification of new items

### 🎨 User Interface
- **Modern design**: Clean interface following Material Design guidelines
- **Intuitive navigation**: Optimized user experience
- **Adaptive theming**: Light and dark mode support
- **Accessibility**: Screen reader and accessibility gesture support

## 🏗️ Architecture

### Project Structure
```
lib/
├── main.dart                 # Application entry point
├── models/                   # Data models
│   ├── shopping_item.dart    # Item model
│   └── shopping_list.dart    # Shopping list model
├── providers/                # State management (Provider)
│   └── shopping_provider.dart # Main provider
├── screens/                  # Application screens
│   ├── home_screen.dart      # Main screen
│   └── history_screen.dart   # History screen
├── services/                 # Business services
│   ├── ai_service.dart       # Artificial intelligence service
│   ├── database_service.dart # Local database service
│   └── sync_service.dart     # Cloud synchronization service
├── utils/                    # Utilities and constants
│   └── constants.dart        # Application constants
└── widgets/                  # Reusable UI components
    └── custom_widgets.dart   # Custom widgets
```

### Technologies Used
- **Flutter 3.16+**: Cross-platform development framework
- **Provider**: Reactive state management
- **SQLite**: Local database (via sqflite)
- **Firebase**: Backend and cloud synchronization
- **HTTP**: API requests for AI services
- **Shared Preferences**: User preferences storage

## 🚀 Installation and Setup

### Prerequisites
- Flutter SDK 3.16.0 or higher
- Dart 3.2.0 or higher
- Android Studio / VS Code with Flutter extensions
- Firebase account (optional, for cloud sync)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/caddy.git
   cd caddy
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase configuration (optional)**
   ```bash
   # Install Firebase CLI
   npm install -g firebase-tools
   
   # Configure Firebase for Flutter
   flutterfire configure
   ```

4. **Run the application**
   ```bash
   # Debug mode
   flutter run
   
   # Release mode
   flutter run --release
   ```

