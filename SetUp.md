# *`SetUp >>`*

```
npx create-expo-app@latest ExpoMyApp
(OR)
npm exec create-expo-app@latest ExpoMyApp
```

```
// For Web
npx expo start
(OR)
npm start
```

```
// For Mobile Use Ngrok
npx expo start --tunnel
(OR)
npm run tunnel
```

```
// Make Android
npx expo prebuild (OR) eas build
(OR)
npm run prebuild
```

```
// Build For APK and AAB // Publish Play Store and Apple.
>> npm install -g eas-cli
>> eas build:configure
// For Production And Play Store Publish.
>> eas build 
   (OR)
   eas build --platform android --profile production
// For Development
>> eas build --platform android --profile preview
```

```
// Guid From ChatGBT For Build
https://chatgpt.com/share/6839a02d-d950-800d-80ee-99f32084e3d5
```
