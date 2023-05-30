# CustomTabbar iOS Project

CustomTabbar is an iOS project that serves as a template for creating a custom tab bar in iOS applications. It demonstrates how to implement a customized tab bar and integrate it into existing projects. The project also showcases deeplink navigation, allowing users to navigate from one view controller to another through deeplinks. The app follows the Coordinator pattern for navigation, adopts the MVVM and clean architecture, and utilizes RxSwift.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Architecture and Design](#architecture-and-design)
- [Installation and Setup](#installation-and-setup)
- [Features and Functionality](#features-and-functionality)
- [API Documentation](#api-documentation)
- [Code Structure](#code-structure)
- [Usage and Configuration](#usage-and-configuration)
- [Troubleshooting and FAQs](#troubleshooting-and-faqs)
- [Known Limitations and Future Enhancements](#known-limitations-and-future-enhancements)
- [Contributing and Support](#contributing-and-support)

## Introduction

The "CustomTabbar" project serves as a template for creating a custom tab bar in iOS applications. It demonstrates how to implement a customized tab bar and integrates it into existing projects. The project also showcases deeplink navigation, allowing users to navigate from one view controller to another through deeplinks. The app follows the Coordinator pattern for navigation, adopts the MVVM and clean architecture, and utilizes RxSwift.

## Prerequisites

To work with the "CustomTabbar" project, ensure that you have the following prerequisites:

- Xcode [Latest]
- iOS [13 or later]
- RxSwift [Latest]

## Architecture and Design

The "CustomTabbar" project adheres to the following architectural principles:

- **MVVM:** The project employs the Model-View-ViewModel (MVVM) architectural pattern. It separates the application's data and logic (ViewModel) from the user interface (View), facilitating better maintainability and testability.
- **Clean Architecture:** The project follows the principles of clean architecture, enabling clear separation of concerns between layers. It consists of three layers: presentation, domain, and data. Each layer has defined responsibilities and dependencies, resulting in a highly modular and scalable codebase.
- **Coordinator Pattern:** The Coordinator pattern is utilized for navigation between view controllers. It centralizes navigation logic, making it easier to manage complex navigation flows and simplifying view controller coordination.

## Installation and Setup

To set up the "CustomTabbar" project, follow these steps:

1. Clone the project repository from [https://github.com/sudiptoroy/CustomTabbar.git].
2. Open the project in Xcode.
3. Install Cocoapods if you haven't already by running the following command in Terminal:

```$ sudo gem install cocoapods```


4. Navigate to the project directory in Terminal and install the project dependencies using Cocoapods:

```$ cd /path/to/project```<br>
```$ pod install```


5. Cocoapods will download and install the specified dependencies, including RxSwift.

Now, your project is set up with RxSwift installed via Cocoapods. Make sure to open the `.xcworkspace` file instead of the `.xcodeproj` file when working with your project to ensure proper dependency integration.

## Features and Functionality

The "CustomTabbar" project provides the following features and functionality:

- **Custom Tab Bar:** The project demonstrates the implementation of a custom tab bar, allowing developers to create visually distinct tab bar interfaces that match their app's design.
- **Deeplink Navigation:** The project showcases deeplink navigation, enabling users to navigate directly to specific view controllers within the app using deeplink URLs.
- **Coordinator Pattern:** The app employs the Coordinator pattern for navigation. It centralizes navigation logic in coordinator classes, providing a scalable and maintainable approach for managing navigation flows.

## API Documentation

The "CustomTabbar" project does not interact with external APIs. Therefore, no API documentation is required.

## Code Structure

The codebase of the "CustomTabbar" project is structured as follows:

- CustomTabbar
  - Coordinator
    - [Coordinator classes]
  - Models
    - [Model classes]
  - ViewControllers
    - [View controller classes]
  - Views
    - [Custom views]
  - ViewModels
    - [ViewModel classes]
  - Utilities
    - [Utility classes]
  - Resources
    - [Asset files and other resources]


## Usage and Configuration

1. Explore the project's codebase to understand the architectural patterns, design choices, and implementation details.
2. Use the `CustomTabbar` module as a reference or template for creating your own custom tab bar in iOS applications.
3. Customize the tab bar appearance, functionality, and behavior to fit your specific project requirements.
4. Incorporate deeplink navigation by following the provided examples and guidelines.
5. Leverage the Coordinator pattern for managing navigation flows in your application.

## Troubleshooting and FAQs

### Troubleshooting

1. **Issue:** The custom tab bar is not displaying correctly on certain devices or orientations.
   - **Solution:** Check the constraints and layout settings for the custom tab bar and its associated views. Ensure that the constraints are properly set to adapt to different screen sizes and orientations.

2. **Issue:** Deeplink navigation is not working as expected.
   - **Solution:** Verify that the deeplink URLs are properly formatted and registered within the app. Check the implementation of the deeplink handling code in the coordinator or view model to ensure the navigation logic is correct.

3. **Issue:** The app crashes when navigating through deeplinks or switching between view controllers.
   - **Solution:** Review the code for potential memory leaks, retain cycles, or improper memory management. Ensure that RxSwift disposables are properly handled and that any strong references to objects are properly weakified.

### FAQs

1. **Question:** Can I customize the appearance of the custom tab bar?
   - **Answer:** Yes, you can customize the appearance of the custom tab bar by modifying the associated views and implementing custom styling and animations.

2. **Question:** How can I add more tabs to the custom tab bar?
   - **Answer:** To add more tabs, you need to create additional view controllers and tab bar items. Follow the existing implementation of the custom tab bar and configure the new view controllers and tab bar items accordingly.

3. **Question:** Can I use this project in an existing project?
   - **Answer:** Yes, you can use this project as a reference or template for creating a custom tab bar in your existing project. However, you may need to adapt the implementation to fit your project's specific architecture and design.


## Known Limitations and Future Enhancements

The "CustomTabbar" project has the following known limitations:

- The current implementation of the project doesn't include any developer account. You will need to configure your own developer account and provisioning profiles to run the app on physical devices or distribute it.
- It cannot be installed with Cocoapods or Swift Package Manager yet. Currently, the project relies on manual integration or copying the necessary files into your project.

Future enhancements for the "CustomTabbar" project could include:

- Integration with Cocoapods or Swift Package Manager for easier installation and dependency management.
- Addition of unit tests and UI tests to ensure code quality and prevent regressions.
- Support for more advanced customization options for the custom tab bar, such as custom animations, transitions, or additional tab bar item styles.
- Integration with a backend service for dynamic tab bar item configurations or remote deeplink handling.
- Improved error handling and user feedback for deeplink navigation failures or invalid deeplink URLs.
- Accessibility enhancements to ensure the custom tab bar and associated components are fully accessible to users with disabilities.
- Compatibility updates to support future versions of iOS and Swift, incorporating new features and best practices.

These limitations and future enhancements provide areas for improvement and expansion of the "CustomTabbar" project.

## Contributing and Support

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

For support or questions, please contact

- sudipto.roy@brainstation-23.com
- asraful.alam@brainstation-23.com
- moshiour.rahman@brainstation-23.com



