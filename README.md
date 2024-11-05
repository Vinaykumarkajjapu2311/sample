# React native using Expo (Javascript)
React Native is a powerful and popular framework for building cross-platform mobile applications using JavaScript and React. It allows developers to use their existing knowledge of React to create native mobile apps for both iOS and Android platforms. If you’re a beginner looking to dive into mobile app development, React Native is a fantastic choice. 

## Understanding React-Native and Expo
React Native is an open-source framework developed by Facebook that enables the creation of mobile applications using the same principles as React, a JavaScript library for building user interfaces. The key concept behind React Native is the ability to write code in a single language (JavaScript) and deploy it across multiple platforms.

### What is Expo?
Expo is an open-source platform built around React Native that simplifies cross-platform mobile development. It extends React Native’s capabilities by packaging essential features and streamlining the development workflow. Overall it improves productivity and reduces the complexity of app development.

### Why Use Expo?
- It has established itself as a powerful framework for React Native developers, offering a streamlined approach to mobile development that simplifies many of the complex tasks typically associated with native development. 
- Expo streamlines development by removing the complexities of platform-specific code, enabling developers to focus on building great user experiences.


## Prerequisites
- React js
- Javascript

## System Requirements
Before you begin with React Native, make sure you have the following prerequisites installed on your machine:

- Node.js and npm: React Native relies on Node.js for running JavaScript code. Install the latest version from the official website.
- Java Development Kit (JDK): Required for Android development. Download and install the JDK from the official Oracle website.
- VS Code : For developing Apps, you’ll need VS Code . Follow the installation instructions from the official website.

## Creating Your First React Native App Using Expo 

### Step 1:
Open your Terminal navigate to the place where you want to create the Project Set Up and run the following Command
```bash
npx create-expo-app --template blank
```
It will ask for the App Name, Give your desired App Name

![image](https://github.com/user-attachments/assets/e4f506fd-21a6-488c-9de8-78d6b0b9da90)

Now your Project is ready and You can get deep Dive:
![image](https://github.com/user-attachments/assets/97e399cb-c156-4df0-8623-fbe7a71ddee0)


### Step 2:
Navigate to the Project by using the following Commands in the terminal:

```bash
cd <Your App Name>
code .
```

![image](https://github.com/user-attachments/assets/612bcac8-1e1a-4fa9-8615-cf1fbba21c0b)

Your Project will open in VS Code 


![image](https://github.com/user-attachments/assets/7b597227-7c6e-43e2-8988-e3ed35fe31e8)

### Step 3:

Knowing the File Structure of the initial Project:

This is the file structure of the  Initial Project:

![image](https://github.com/user-attachments/assets/7586bff2-2ccb-40ab-a1a2-30668e7b2916)

#### This is the typical file structure of an Expo React Native app:

- **.git** - Directory containing Git-related files, used for version control.

- **.vscode** - Contains settings specific to Visual Studio Code, such as workspace configuration.

- **assets** - Folder for storing images, fonts, and other static assets used in the app.

- **node_modules** - Directory where all the app dependencies and packages installed via npm or yarn are stored.

- **.gitignore** - Specifies files and directories that should be ignored by Git (like node_modules).

- **App.js** - The main entry point of the app. This file contains the root component where you define the app's main structure and logic.

- **app.json** - Configuration file for the Expo app. It contains metadata such as app name, icon, and other Expo-specific settings.

- **babel.config.js** - Babel configuration file, used for transpiling JavaScript code to ensure compatibility across different environments.

- **package-lock.json** - Automatically generated file that locks the exact versions of installed dependencies to ensure consistency across environments.

- **package.json** - Contains metadata about the project, including dependencies, scripts, and basic project information.

### Step 4: Creating the Hello World Program

As App.js is the main Entry Point Replace the existing Code in App.js with the following Code:

```bash
import { StatusBar } from 'expo-status-bar';
import { StyleSheet, Text, View } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text>Hello World</Text>
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});
```

### Step 5:

Run the App i.e Start the Expo Development Server.

1.Install the Expo Go app on your device from the App Store or Play Store 

Expo Go is a sandbox environment that allows you to experiment with building native Android and iOS apps. It's a good starting point for beginners and experienced developers who want to transition to cross-platform mobile development. 

2. Start the Development Server:

   - Open Terminal in VS Code
     ![image](https://github.com/user-attachments/assets/2e59ebbc-d6e5-497d-959f-7780487a5c84)
   - Enter the following Command to start the development Server:
       ```bash
       npx expo start
       ```
   - You will get  a QR like this
   
      ![image](https://github.com/user-attachments/assets/1446e5bc-92e3-4774-850c-1ce71a19c65c)

 3. Open the Expo Go Application on your Mobile and Scan the QR.
    (Ensure that your PC and Mobile are Connected to the same Network, the build might fail sometimes due to different networks)
    
     Congratulations! You've just built your very first Mobile App!

    Output Looks Similar to this:
    
    ![image](https://github.com/user-attachments/assets/a2fdfc9b-0b24-4ca6-b36f-ef1e5a888326)

## Assignment :
Explore the following React Hooks which are widely used in React Native App Development:

useState

useEffect

useContext

useReducer

useRef

useMemo

useCallback

useLayoutEffect

useImperativeHandle

useDebugValue



## Projects for Practice :

### **Stopwatch/Timer App**
**Description:** Create a stopwatch or timer with start, pause, and reset functionalities.
**Skills:** Using useState and useEffect for timing logic, handling UI updates based on timer status.

### Simple Quiz App
**Description:** A quiz app where users can select answers and get a score at the end.
**Skills:** State for tracking current question, selected answers, and scoring based on answers.





       



