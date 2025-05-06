# Mental Health App UI

A beautifully designed Flutter application showcasing a modern mental health app interface. This project demonstrates the implementation of complex UI components while following best practices in state management and architecture.

## Features

- 🎨 Modern and intuitive user interface
- 📱 Responsive design for various screen sizes
- 🔄 State management using BLoC pattern
- 📦 Feature-driven architecture
- 🗺️ Bottom navigation with BLoC integration
- 🎭 Interactive emotion selection
- 👋 Personalized user greetings

## Architecture

This project follows a feature-driven architecture pattern, organizing code by features rather than technical layers. The key architectural components include:

### BLoC (Business Logic Component)
- Separation of UI and business logic
- Predictable state management
- Efficient handling of UI events and states
- Integration with BottomNavigationBar for seamless navigation

### Feature-Driven Structure
```
lib/
  ├── home/
  │   ├── bloc/
  │   │   ├── home_bloc.dart
  │   │   ├── home_event.dart
  │   │   └── home_state.dart
  │   ├── screens/
  │   │   └── home_page.dart
  │   └── widgets/
  │       ├── bottom_nav_bar.dart
  │       ├── emoticon_card.dart
  │       └── greet.dart
  └── main.dart
```

## Getting Started

### Prerequisites
- Flutter SDK (>=2.19.2 <3.0.0)
- Dart SDK
- Android Studio / VS Code with Flutter extensions

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/mental_health_app_ui.git
```

2. Navigate to project directory
```bash
cd mental_health_app_ui
```

3. Install dependencies
```bash
flutter pub get
```

4. Run the app
```bash
flutter run
```

## Dependencies

- `flutter_bloc: ^8.1.2` - State management
- `cupertino_icons: ^1.0.2` - iOS-style icons

## Design Inspiration

The UI design is inspired by a concept from Dribbble:
- [Original Design](https://dribbble.com/shots/15002657-Mental-Health-App)

![App Design Preview](https://user-images.githubusercontent.com/64529996/220638625-8c4ef686-2a26-4e26-981c-82decaa9a4e4.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Learn More

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

