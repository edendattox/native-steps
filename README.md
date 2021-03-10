 Native-steps -:
 
1 react native app setup
 
 step-1 :  install expo cli npm install -g expo-cli.
 step-2 :  Then run the following commands to create a new React Native project called "AwesomeProject":
 
           expo init AwesomeProject

           cd AwesomeProject
           npm start # you can also use: expo start.
           
2 navigation setup -:

step-1 : Install the required packages in your React Native project: npm install @react-navigation/native

step-2 : createStackNavigator 
         (Provides a way for your app to transition between screens where each new screen is placed on top of a stack.
         By default the stack navigator is configured to have the familiar iOS and Android look & feel: new screens slide in from the right on iOS, fade in from the bottom on              Android. On iOS the stack navigator can also be configured to a modal style where screens slide in from the bottom.)
         
         npm install @react-navigation/stack.
         
         visit site for docs https://reactnavigation.org/docs/stack-navigator/.
         
step-3 : Installing dependencies into an Expo managed project#
         In your project directory, run:

         expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
         This will install versions of these libraries that are compatible.

         You can now continue to "Hello React Navigation" to start writing some code.         


3 react native tags -:

1.  view = div;
2.  onClick = onPress;
3.  navigation.navigate to go to mention page or slide.
4.  

4 react firebase setup

step-1: First we need to setup a Firebase Account and create a new project. We will be using the JavaScript SDK provided by Firebase, so pull it into your Expo project.

        expo install firebase  
        
        and for futrther info read documentation on expo firebase.
        
        
        
        
        
        
        
