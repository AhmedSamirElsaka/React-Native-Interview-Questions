# React Native Interview Questions & Answers

> Click :star: if you like the project and follow [@AhmedSamirElsaka](https://github.com/AhmedSamirElsaka) for more updates

---

### Table of Contents

<!-- TOC_START -->
| No. | Questions |
| --- | --------- |
| 1 | [What is React Native and how does it differ from React?](#What-is-React-Native-and-how-does-it-differ-from-React) |
| 2 | [Explain the concept of JSX in React Native](#Explain-the-concept-of-JSX-in-React-Native)|
| 3 | [How do you create a component in React Native?](#How-do-you-create-a-component-in-React-Native?)|
| 4 | [What are the advantages of using React Native?](#What-are-the-advantages-of-using-React-Native?)|
| 5 | [What are the key differences between React Native and ReactJS?](#What-are-the-key-differences-between-React-Native-and-ReactJS?)|
| 6 | [How do native apps differ from hybrid apps?](#How-do-native-apps-differ-from-hybrid-apps?)|
| 7 | [What products and apps is React Native best used for?](#What-products-and-apps-is-React-Native-best-used-for?)|
| 8 | [What are the core components of React Native?](#What-are-the-core-components-of-React-Native?)|
| 9 | [What is component-driven development?](#What-is-component-driven-development?)|
| 10 | [What is the role of props in React Native?](#What-is-the-role-of-props-in-React-Native?)|

<!-- TOC_END -->


<!-- QUESTIONS_START -->
1. ### What is React Native and how does it differ from React
    ---
    React Native is a framework for building mobile applications using JavaScript and React. It enables the development of cross-platform apps with a single codebase that runs on both iOS and Android.     
    While React is primarily for building web interfaces, React Native focuses on mobile UI components. React Native uses native components, providing a more authentic feel and better performance than  web-based solutions.

2. ### Explain the concept of JSX in React Native.
   ---
   JSX (JavaScript XML) is a syntax extension in React Native that allows embedding HTML-like elements within JavaScript code. It simplifies UI rendering by letting developers write components using a familiar HTML structure. JSX gets transpiled into JavaScript, enabling React Native components to be expressed in a more readable and intuitive format.

3. ### How do you create a component in React Native?
   ---
   To create a component in React Native, you define a JavaScript function or class that returns JSX elements. For example:
   
    ```javascript
    import React from 'react';
    import { View, Text } from 'react-native';

    const MyComponent = () => {
    return ( <View>
            <Text>Hello, React Native!</Text>
        </View>);
    };
    
     export default MyComponent;
      ```
    
4. ### What are the advantages of using React Native?
   ---
   Since its launch in 2015, React Native has built a reputation as a reliable and effective JavaScript framework. Some of its key strengths include:

    1. **Cross-platform compatibility:** Most of the code is cross-platform, meaning developers only have to create one app rather than two separate apps for both iOS and Android
    2. **Real-time feedback:** React Native offers a ‘hot reloading’ feature where developers can immediately view the changes they’ve made in a separate preview window
    3. **Flexible user interface:** React Native’s interface is slick and makes it easy for multiple developers to work on a project together
    4. **Third-party plugins:** React Native is compatible with many third-party plugins that can be used to support and improve the app development process
    5. **Community:** As a popular open-source framework, React Native has a large community of developers that exchange knowledge

5. ### What are the key differences between React Native and ReactJS?
   ---
   React Native is used to develop mobile apps for iOS and Android, whereas ReactJS is used to build web apps in a web browser.                                                                           
   Both use reusable JavaScript XML components, but the syntax varies: React Native uses app-view components, and ReactJS uses HTML tags.

6. ### How do native apps differ from hybrid apps?
   ---
   Hybrid apps are developed to be used across all platforms, whereas native apps are developed for a particular platform. React Native is used for the development of hybrid apps.                       
   While hybrid apps are faster to develop and typically require less maintenance than native apps, they may perform slightly worse than their native counterparts.

7. ### What products and apps is React Native best used for?
   ---
   React Native is a great option for developing a hybrid app that does not require extremely high performance.                                                                                           
   Cross-platform compatibility means development teams can save lots of time when using React Native compared to a native framework.                                                                     
   However, it might not be suitable when designing complex apps or if developers aren’t already well-versed in React code.

8. ### What are the core components of React Native?
   ---
   Components are the building blocks of React Native; when combined, they make up the app as a whole. Some of the most common components are:
   1. **View :** used to display the entire app layout
   2. **Text :** used to display text
   3. **TextInput :** used to input text
   4. **ScrollView :** used to insert a scrolling container
   5. **StyleSheet :** used to insert style objects
   6. **Image :** used to render images
   7. **Button :** used to insert buttons

9. ### What is component-driven development?
   ---
   Component-driven development (CDD) is a development methodology where the build process is anchored around components rather than objects. Components are loosely coupled and each one serves its own     purpose.                                                                                                                                                            
   When put together, components (buttons, navigation bars, images) form the program as a whole. React Native is a component-driven framework.

10. ### What is the role of props in React Native?
    ---
    Props provide properties to components inserted in a program, which makes components modifiable and customizable.                                                            
    For example, the same component might be used in different parts of an app.                                                                                                        
    When we use props, we can alter the component’s appearance or behavior. 
