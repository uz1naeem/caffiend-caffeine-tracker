# Caffiend - Your Coffee Tracking Companion

## Overview
Welcome to **Caffiend**, the ultimate app for coffee enthusiasts looking to track their caffeine consumption and expenses. Coffee spending habits can add up quickly, and Caffiend provides a fun and interactive way to visualize total coffee spending over time. This project allowed me to dive deep into **Firebase** while honing my skills in full-stack development. 

Using scientific insights, the app also calculates caffeine levels in the blood based on the caffeine half-life, which is approximately five hours. By inputting consumption data, users can visualize how their caffeine levels change over time, helping them make informed choices about their next brew!

## Features

### Technical Features
- **Data Persistence with Firebase Firestore**: When users log their coffee consumption through a form, the app creates and stores data objects in Firebase Firestore. This involves constructing a new object containing coffee details (name, cost, consumption time) and leveraging Firestore's real-time capabilities to ensure that updates reflect immediately across all user sessions.

- **User Authentication**: By utilizing Firebase Authentication, the app enables secure sign-up and login processes. This involves creating a user account with email and password, validating inputs, and handling authentication states to manage access to user-specific data seamlessly.

- **React Context for State Management**: The application employs React Context to manage global state, including user authentication and coffee consumption history. This pattern helps keep the UI in sync with the underlying data and allows easy data sharing across components without prop drilling.

- **Dynamic Data Calculation**: The app computes real-time statistics, such as daily caffeine intake and total spending. The caffeine level calculations take into account the half-life of caffeine to estimate how much caffeine remains in the user’s system, providing insights into their consumption patterns.

### App Features
- **Coffee Entry Form**: The intuitive form allows users to specify the type of coffee, its cost, and the time since consumption. This form is powered by controlled components, where each input value is tied to state variables, ensuring a smooth user experience.

- **Consumption History**: Users can view their historical coffee entries in a neatly formatted timeline. Each entry displays essential details like coffee name, consumption time, and cost, giving a comprehensive overview of past habits.

- **Caffeine Statistics Dashboard**: The dashboard dynamically updates to show users their active caffeine levels and consumption trends. This feature includes visual indicators for caffeine status (low, moderate, high) based on half-life calculations, making it easy to understand how much caffeine remains in the system.

## Contributing

Contributions from the community are welcome! If you’d like to help improve Caffiend, here’s how you can get started:

1. **Fork the Repository**: Click on the "Fork" button at the top right of this repository to create your own copy of the project.

2. **Clone Your Fork**: Use the "Code" button to copy the URL and run:
   ```bash
   git clone <your-fork-url>

3. **Create a Branch**: Navigate to the project directory and create a new branch:
   ```bash
   git checkout -b my-feature

4. **Make Changes and Commit**: Edit, then add and commit your changes:
   ```bash
   git add .
   git commit -m "Add my feature"

5. **Push and Create a Pull Request**:  Push your branch and submit a pull request on GitHub.

### Conclusion

Caffiend not only fosters a community of coffee enthusiasts but also empowers users to take control of their caffeine consumption and spending. By effectively leveraging modern technologies like Firebase for data management, it offers a practical solution for visualizing habits and costs. This project serves as an engaging exploration into the world of caffeine tracking while providing a valuable tool for those looking to make informed decisions about their coffee intake.
