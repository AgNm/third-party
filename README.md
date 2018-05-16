# third-party

This folder contains third-party folder to resolve below error :

Lexical or Preprocessor Issue
'config.h' file not found

Steps:
1. Go to Project -> node_modules -> react_native
2. Remove third-party folder 
3. Add this one
4. run : npm install on root folder
5. run : react-native bundle --platform ios --dev false --entry-file index.ios.js --bundle-output iOS/main.jsbundle
6. Then build


