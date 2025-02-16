# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

## Project Restructuring Script

This script effectively restructures your React Native project while preserving a backup of your existing files for reference. Here's a breakdown of what happened:
Key Actions Performed:

### Backup of Existing Files

The script asked if you'd like to move existing project files (like /app, /components, /hooks, /constants, and /scripts) into a backup directory named /app-example instead of outright deleting them. You chose "Y", so your old files are now safely stored in /app-example.

#### Reorganization  

A new /app directory was created, following what appears to be a more modern or structured file organization (perhaps influenced by Expo's new directory-based routing).

Two new files were added:

- app/index.tsx: Likely serves as the main entry point for your application.
- app/_layout.tsx: Could be a layout file for routing or a template for app-wide components like headers or footers.

Reset Complete:

The script leaves clear instructions for next steps:

- Start the development server using npx expo start.
- Modify app/index.tsx to update your main screen.
- Delete the /app-example directory when you're done referencing your old project files.
