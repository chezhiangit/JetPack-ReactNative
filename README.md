# JetPack-ReactNative
React Native base template project. This template is configured with Redux, react-redux, redux-thunk. 

# pls refer the pdf attached to configure proxiy.

# How to use
1. Download the project.
2. Do "npm install" from root folder of the project.
3. Do react-native link.
4. Open new terminal. navigate to root folder of the project and type "npm start".
5. Open new termina. navigate to root folder of the project and type "react-native run-ios' or "react-native run-android".
#Add Custome fonts
React-Native just uses the default font family for each platform. So that's San Francisco on IOS and Roboto for Android
To add custom fonts for your project, add new font family (.ttf or otf) into the foloder 'app/assets/fonts'. Once added the required fonts, got to terminal and run "react-native link". This will link the font to android project and also ios project. You can verify the same in the android assets folder and ios fonts floder.
