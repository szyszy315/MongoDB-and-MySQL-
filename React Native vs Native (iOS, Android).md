React Native vs Native (iOS, Android).md
====

what is react Native
----
React Native is a framework created by Facebook that allows you to develop native mobile apps for iOS and Android with a single JavaScript codebase.<br>
React Native uses a set of components such as \<Image>, \<View>, \<ScrollView>, \<TextInput>, \<FlatList> which map to their native iOS and Android counterparts, as well as some platform-specific components such as \<DatePickerIOS> and \<ProgressViewIOS> for iOS or \<ViewPagerAndroid> and \<ToastAndroid> for Android.<br>

cons:<br>

1.React Native enables a single JavaScript codebase for 2 different platforms. This means that it is not just easier to maintain the app by having the same development process for both platforms and reusing the same code, but it also requires less resources, because there is no need for separate iOS and Android teams.<br>
2.React Native is based on React.js, which is written in JavaScript. 
3.React Native’s approach to structuring UI is Flexbox, which is already very popular in web development and enables the developer to create a responsive web or mobile UI very easily. <br>

pro:<br>
1.If the project requirements dictate that specific OS requirements should be followed for each native platform, React Native developer will need to write platform-specific code, which defeats the purpose of the single codebase. This might be a bigger issue when it comes to iOS, because Apple often updates and deprecates their technologies which can be hard to follow<br>
2.even with the factor of being allowed to write an app that looks the same on both platforms, it is still impossible to write an app without writing any platform-specific code.

User Interface
----
React Native’s approach to structuring UI is Flexbox, which is already very popular in web development and enables the developer to create a responsive web or mobile UI very easily.

The programming language
----
React Native is based on React.js, which is written in JavaScript.JavaScript remains one of the most widely-used programming languages in the world, and the maturity of the JavaScript community implies that finding a React Native developer for a project should typically be trivial.

Native modules
----
While React Native can handle a large amount of cross-platform use cases, it is impossible for it to cover all the native mobile ground. 
Native modules are basically code in native language which handles a specific native feature. 
Conclusion
----
In these situations react native is more preferable:<br>
1. need to make an app for both platform.<br>
2. need features such as hot reloading and live reloading.<br>
3. developers have a strong React / Web development background.<br>
4. app going to look and behave the same on both platforms.<br>

In these situations native is more preferable:<br>
1. just want to make a make an iOS-only or Android-only app.<br>
2. plan to maintain the app over a long period of time.<br>
3. need to support new mobile OS features as soon as they are released.<br>
