# Uber Project

Welcome to the Uber Project! This is a React Native app developed for iOS that simulates some functionalities similar to Uber.

## Project Link

You can find the project repository on GitHub: [Uber](https://github.com/AbdelmajidBen/Uber)

## Technologies Used

- **React Native**: For building the app.
- **Tailwind CSS**: For styling the components.
- **React Native Elements**: For UI components.
- **React Native Vector Icons**: For icons.
- **Redux Toolkit**: For state management.
- **Expo**: For development and building.

## Prerequisites

- **Xcode**: To run the app on an iOS simulator.
- **Node.js**: To manage npm packages.
- **Expo CLI**: To start the project.

## Installation

Follow these steps to get the project up and running on your local machine:

1. **Clone the repository**

```bash
git clone https://github.com/AbdelmajidBen/Uber.git
cd Uber
```

2. **Install the dependencies**

```bash
npm install
```

3. **Start the project**

```bash
npx expo start
```

4. **Run the app on an iOS simulator**

When the Expo CLI starts, type `i` to open the app in the iOS simulator.

## Dependencies

Here is a list of all the dependencies used in this project along with their versions:

- **@expo/metro-runtime**: ~3.2.1
- **@reduxjs/toolkit**: ^2.2.6
- **expo**: ~51.0.18
- **expo-status-bar**: ~1.12.1
- **react**: 18.2.0
- **react-dom**: 18.2.0
- **react-native**: 0.74.3
- **react-native-elements**: ^3.4.3
- **react-native-safe-area-context**: ^4.10.7
- **react-native-vector-icons**: ^10.1.0
- **react-native-web**: ~0.19.10
- **react-redux**: ^9.1.2
- **twrnc**: ^4.3.0
- **@react-navigation/native**: ^6.1.17
- **@react-navigation/stack**: ^6.4.0
- **react-native-dotenv**: ^3.4.11
- **react-native-gesture-handler**: ^2.17.1
- **react-native-google-places-autocomplete**: ^2.5.6
- **react-native-maps**: ^1.15.6
- **react-native-maps-directions**: ^1.9.0
- **react-native-screens**: 3.31.1

## Running the App

To run the app, ensure you have Xcode installed on your machine for iOS simulation. After starting the project with `npm expo start`, type `i` to launch the app in the iOS simulator.

## Google Maps API Key

You will need to create a Google account and enter your billing information to generate your private key for accessing the distance matrix, time duration, etc. Place your API key in a file named `.env` with the following format:

```
GOOGLE_MAP_API_KEY=your_api_key_here
```

## License

This project is licensed under the MIT License.

---

Developed by Abdelmajid Ben
