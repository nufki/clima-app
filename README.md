# Clima app ☁
This simple app uses geolocation and interacts with API's from openweather.com.
The api's will provide live weather data in the current location of the device as well as the weather for any city you input.

# Deploy the app on IOS (native device)
1. Initial setup: run: `open ios/Runner.xcworkspace`, set team (yourself probably)
2. Then run this command below running the build above manually on xcode runs it in debug mode only
````
flutter run --release  
````
This command builds and runs your Flutter app on a connected device (physical device or emulator/simulator) in release mode.