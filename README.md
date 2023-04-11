# covid_tracker

Overview:
Covid Tracker is a Flutter application that provides real-time statistics on Covid-19 cases across the world. It displays the global and country-wise number of confirmed, recovered, and deaths due to Covid-19. The app fetches data from an external API and uses various third-party packages to display the data and add animations to the UI.

APIs and Data Sources:
The app uses the disease.sh API to fetch data related to Covid-19 cases. The API provides real-time data on global cases, cases per country, and historical data. The API URLs are defined in the app_url.dart file located in the services/utilities folder.

Packages:
The following packages are used in the project:

http: ^0.13.4 - Used to make API requests to fetch data from the disease.sh API.
animated_text_kit: ^4.2.1 - Used to add animations to the UI such as fading and color changing text.
pie_chart: ^5.1.0 - Used to display the global and country-wise Covid-19 cases in a pie chart format.
flutter_spinkit: ^5.1.0 - Used to add a loading spinner while fetching data from the API.
shimmer: ^2.0.0 - Used to add a shimmer effect to the UI while data is being fetched.
Use of Packages:

The http package is used to make GET requests to the disease.sh API and fetch Covid-19 data.
The animated_text_kit package is used to add animations to the app UI, such as changing text colors and fading in/out text.
The pie_chart package is used to display global and country-wise Covid-19 cases in a pie chart format.
The flutter_spinkit package is used to add a loading spinner to the UI while data is being fetched.
The shimmer package is used to add a shimmer effect to the UI while data is being fetched.
Animations:
AnimatedTextKit and Shimmer are used to add animations to the UI. AnimatedTextKit is used to animate the text in the splash screen, while Shimmer is used to add a shimmer effect to the UI while data is being fetched.


File and Folder Descriptions:

lib/model
This folder contains the world_stats_model.dart file, which defines the data model for the app.

lib/services
This folder contains the stats_services.dart file, which is responsible for fetching the COVID-19 statistics data from external APIs. It also contains the utilities folder, which includes the app_url.dart file that stores the URLs for the APIs used in the app.

lib/view
This folder contains the different screens used in the app:

countries_list.dart displays a list of countries and their COVID-19 statistics.
detail_screen.dart displays detailed information about a selected country's COVID-19 statistics.
splash_screen.dart displays the app's splash screen when it is launched.
world_stats.dart displays the worldwide COVID-19 statistics.

lib/main.dart
This is the main entry point for the app, where the MaterialApp widget is defined.

Installation Instructions:

To install the app, follow these steps:
Clone the repository to your local machine using git clone.
Run flutter pub get to install the dependencies.
Run flutter run to launch the app on a simulator or physical device.

Usage Instructions
When you launch the app, you will see the splash screen followed by the world COVID-19 statistics. You can then navigate to the Countries List screen to view a list of countries and their COVID-19 statistics. Tapping on a country will take you to the Detail Screen for that country, where you can see more detailed information.


Contributing
If you would like to contribute to the project, please fork the repository and submit a pull request with your changes. Be sure to follow the project's coding standards and provide detailed documentation for any new features or changes.

Contact
If you have any questions or issues with the app, please contact at 
Email: burhanmujahid552@gmail.com
Linkedin: https://www.linkedin.com/in/muhammad-burhan-mujahid/


