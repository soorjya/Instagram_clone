# Instagram Clone

This repository contains an Instagram clone built using Flutter, Dart, and Firebase. It aims to replicate the core functionality and user interface of the popular social media platform Instagram.

## Features

- User Authentication: Sign up, sign in, and password reset functionality using Firebase Authentication.
- User Profile: Edit profile information, including profile picture and bio.
- Feed: Scroll through a feed of posts uploaded by users, including images and captions.
- Likes and Comments: Like and comment on posts, with real-time updates using Firebase Firestore.
- Follow/Unfollow: Follow and unfollow other users, with the ability to see their posts in the feed.
- Explore: Discover new posts and users through a curated explore section.
- Notifications: Receive real-time notifications for likes, comments, and new followers.
- Direct Messaging: Send and receive private messages to other users.

## Screenshots

Include a few screenshots or a GIF demonstrating the user interface and key features of the app.

## Getting Started

### Prerequisites

- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart SDK: [Install Dart](https://dart.dev/get-dart)

### Installation

1. Clone the repository:
   ```sh
 https://github.com/soorjya/instagram-clone.git

```

2. Navigate to the project directory:

```sh

cd instagram-clone
```
3. Install the required packages:

```sh

flutter pub get
```

## Configuration

1. Create a new Firebase project: [Firebase Console](https://console.firebase.google.com/u/0/?pli=1).
2. Set up Firebase Authentication and Firestore for your project.
3. Copy the Firebase configuration files into the project:
    - Android: Copy `google-services.json` into `android/app/` directory.
    - iOS: Copy `GoogleService-Info.plist` into `ios/Runner/` directory.


##  Usage


1. Start the app:

```sh

flutter run

```
2. The app will be launched on connected devices or emulators.

## Contributing
Contributions are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License
This project is licensed under the [MIT License](https://opensource.org/license/mit/)

## Acknowledgements
- This project is inspired by the user interface and functionality of Instagram.
- Thanks to the Flutter and Dart communities for providing excellent tools and resources.
- Special thanks to Firebase for their robust backend services.


```sql


Feel free to customize and enhance the README file based on your specific implementation, additional information, and styling preferences.

```



