# Flutter Post Cards

A simple and attractive Flutter application that fetches posts from an API and displays them in a card view. Each card displays a post title and a snippet of its content. When a card is tapped, a detailed view of the post is shown in a popup dialog.

## Features

- Fetches posts from an online API.
- Displays posts in a card layout.
- Shows detailed post information in a dialog when a card is tapped.
- Responsive and smooth user interface.

## Screenshots

![Home Screen](screenshots/home_screen.png)
![Post Details](screenshots/post_details.png)

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- An IDE with Flutter support (VS Code, Android Studio, etc.)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/flutter_post_cards.git

2. **Install dependencies:**

   ```bash
   flutter pub get

3. **Run the app:**

   ```bash
   flutter run

### Important Files

- `lib/main.dart`: The main file where the app starts.
- `pubspec.yaml`: The file that manages the app's dependencies.

### Dependencies

- http: A package for making HTTP requests.
- flutter/material.dart: Material Design components for Flutter.

### API Reference

This project uses the following API to fetch posts:
- [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts): A free online REST API for testing and prototyping.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

