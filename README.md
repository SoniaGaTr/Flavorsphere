# **Flavorsphere**

Flavorsphere is an Android mobile application developed in Java, using Gradle as the build system. The app allows users to search for and save their favorite recipes 
from an external API, easily share them through various platforms, and manage their account with login options.

## Authors
- Sonia Gallego Trapero [SoniaGaTr](https://github.com/SoniaGaTr)
- Isabella Chaves Gómez [isabellachgo](https://github.com/isabellachgo)
- Fernando Prados Vicente [Fernando-Prados](https://github.com/Fernando-Prados)

## Table of Contents

* [Download project](#download-project)
* [Technologies](#technologies)
* [Project organization](#project-organization)
* [How to use](#how-to-use)

## Download project ##
### Prerequisites ###
- [Java JDK](<https://www.oracle.com/java/technologies/javase-downloads.html>) (versión 8 o superior)

### Instructions ###
1. Clone the git repsitory:  `git clone https://github.com/SoniaGaTr/Flavorsphere.git`
2. Open the project in Android Studio.
3. Ensure dependencies are configured in build.gradle.
4. Build and run the app on a physical device or emulator.

## Technologies ##
* Language: Java
* Build System: Gradle
* Platform: Androi

## Project organization ##

The project is organized into the following main directories and files:

* `app`
  * `java/es.upm.etsiinf.myapplication`: Contains the core Java classes for the app.
    * `activities`: Includes Activity classes, such as MainActivity, LoginActivity, and RecipeDetailActivity.
    * `adapters`: Holds the adapter classes for managing the display of recipe lists.
    * `models`: Contains model classes to represent the data structure.
    * `listeners`: Includes custom listeners for handling user interactions and events within the app.
    * `interfaces`: Defines interfaces to facilitate communication between components.
    * `requestManagers`: Manages API requests, with classes dedicated to connecting and handling responses from the external recipe API.
    * Activity classes and additional files to support main application functionality.
  * `res`
    * `layout`: XML files for UI layouts.
    * `values`: Resources for consistent styling and localization.
    * `drawable`: Holds images and icons used within the app.
    * `font`: Custom fonts for styling text in the app.
    * `mipmap`: Launcher icons for different screen resolutions.

## How to use ##
When opening the application, a login screen is displayed, with the option to 'remember' so that the session remains open the next time the application is opened. The user can log out, which means that they will have to log in again. In the current version, the functionality to register new users is not implemented, only the user 'Olivia' with password '1234Abc' is available.

On the main screen of the application, there is a search engine that will return a list of recipes from an external API. The user can mark recipes as favorites, these will appear in the favorites section, and they can also remove recipes from their favorites. Recipes can be shared outside the application, for example by email.

The application also has welcome notifications when logging in.


