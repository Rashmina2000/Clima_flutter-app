# Clima
<img src="https://github.com/user-attachments/assets/a239a149-ea4e-4142-ae5b-7cf9e0f2a790" width="250">
<img src="https://github.com/user-attachments/assets/98852c75-12e6-477f-923e-f33d1a3129c2" width="250"><br><br>
<img src="https://github.com/user-attachments/assets/09611373-7cd0-4aef-9a1e-75bc09b9df87" width="250"><br><br>

-   Clima is a Flutter mobile application that provides real-time weather data sourced from [OpenWeatherMap](https://openweathermap.org) using an [API service](https://openweathermap.org/api) provided by OpenWeatherMap.
-   Clima tracks your location using your device's GPS location.
-   You can also get weather data for any city you like.
-   This app gives the temperature and little message tip according to the corresponding city's weather.
<br><br>

## Built With

* ![Flutter](https://img.shields.io/badge/Flutter-02569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
* ![Dart](https://img.shields.io/badge/Dart-0175C2.svg?style=for-the-badge&logo=Dart&logoColor=white)
<br><br>

## Getting Started
### 💻 Requirements

- Any Operating System (ie. MacOS X, Linux, Windows)
- Any IDE with Flutter and Dart SDKs installed (ie. IntelliJ, Android Studio, VSCode etc)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Rashmina2000/Clima_flutter-app.git
   ```
2. Navigate into the directory:
   ```sh
   cd Clima_flutter-app
   ```
3. Get the dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app:
   ```sh
   flutter run
   ```
<br>

## Usage
In order to get weather data from OpenWeatherMap, you need to have a API key provided by OpenWeatherMap.<br>
Register to the [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) website and obtain a API key for make api requests. You'll get a API key similar to the one in below image. You can get this for free.

![OpenWeatherMap](https://github.com/user-attachments/assets/c94a5062-deee-44de-9097-73043ed366d6)<br><br>

Then copy that key to the `apiKey` constant in `lib/services/weather.dart` file.

![code](https://github.com/user-attachments/assets/110d0d45-aa45-482d-942d-735ad0ba51ed)<br>

> 💡 Note that there are limitations in free API services. refer the documentation of OpenWeatherMap for more details.

<br><br>

## Contact

Project Link: [https://github.com/Rashmina2000/Clima_flutter-app.git](https://github.com/Rashmina2000/Clima_flutter-app.git)
<br><br>

## Acknowledgments

Made with 
-  [geolocator 12.0.0](https://pub.dev/packages/geolocator)
    -  Plugin which provides easy access to platform specific location services.

-  [flutter_spinkit 5.2.1](https://pub.dev/packages/flutter_spinkit)
    -  A collection of loading indicators animated with flutter.

-  [http 1.2.2](https://pub.dev/packages/http)
    -  A composable, Future-based library for making HTTP requests.

-   [https://openweathermap.org/api](https://openweathermap.org/api)
      -   API service for real time weather data.  
