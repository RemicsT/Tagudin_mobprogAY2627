# Lab Activity 0A: Flutter Installation and Project Setup
# Lab Activity 0B: Running Your First Flutter Application
## Laboratory Discussion

**1. What challenges did you encounter while installing or configuring Flutter?**

I encountered challenges configuring the Flutter SDK path and setting up the Visual Studio Code integrated terminal. Initially, Flutter was not recognized as a command because its `bin` directory was not properly configured in the environment variables. I also experienced a terminal launch error related to ConPTY compatibility in VS Code.

**2. Did you encounter any errors when running `flutter doctor`?**

Yes. Initially, Flutter Doctor reported that the Android SDK could not be located. It also indicated that Microsoft Visual Studio was not installed. When attempting to launch the Android Emulator, I encountered an issue because Windows Hypervisor Platform was not enabled.

**3. How did you resolve installation, dependency, SDK, or device-related issues?**

I configured the Flutter SDK's `bin` directory in the system PATH and adjusted the VS Code terminal settings. I also downgraded VS Code to resolve the terminal compatibility issue. To address the missing Android SDK, I installed Android Studio and its required SDK components. Since I did not have an Android phone and could not enable the Android Emulator, I used Google Chrome to run and test my Flutter application successfully.

**4. What did you learn about configuring a Flutter development environment?**

I learned that setting up a Flutter development environment requires more than simply installing the Flutter SDK. It is important to configure environment variables correctly, install the necessary development tools, verify dependencies using Flutter Doctor, and prepare an available device or browser for application testing.

**5. What practices will you follow to make future Flutter development easier?**

I will maintain an organized project directory, ensure that my development tools and dependencies are properly configured, regularly run `flutter doctor` to identify potential issues, and test my applications frequently. I will also document errors and their solutions to make future troubleshooting more efficient.

Lab Activity 0B: Discussion

1. What was your experience creating and running your first Flutter application?

Creating my first Flutter application was a valuable learning experience. I was able to create a project using the Empty Application template, explore its file structure, and run it successfully using Google Chrome.

2. What challenges did you encounter with dependencies, SDK configuration, or device selection?

One challenge was selecting an appropriate testing device because I do not have an Android phone. I also needed to configure the Android SDK and resolve some development environment issues during the previous activity.

3. Did you encounter any errors, and how did you troubleshoot them?

I initially encountered configuration issues with the Flutter SDK and Android emulator. I resolved the Android SDK issue through Android Studio and used Google Chrome as an alternative testing platform. I also executed flutter pub get to ensure that the project dependencies were available.

4. What did you learn about executing Flutter applications?

I learned how to execute Flutter applications using the terminal and how to select an available device for testing. I also learned that Flutter supports multiple platforms, including web browsers, allowing developers to test applications without a physical Android device.

5. What best practices will you apply in future mobile development activities?

I will keep my project files organized, regularly check dependencies, use flutter doctor to verify my development environment, and test my applications frequently. I will also save my progress using Git and GitHub to maintain an updated copy of my projects.