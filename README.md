# DevEco-Studio
## DevEco-Studio IDE Hub
### V2.1 Release (2021-06-02)
#### New Features
- Added the cross-device project templates, allowing you to follow the project wizard to create cross-device projects and develop cross-device apps. Changes to the project wizard:

	-  Earlier version: Select a device and then a project template.
	- Current version: Select a project template and then a supported device type. For details, see [Creating a Project](https://developer.harmonyos.com/en/docs/documentation/doc-guides/create_new_project-0000001053342414 "Creating a Project").

- Added the project wizard for developing the Atomic Services – a HarmonyOS service mode that is future-oriented. Atomic Services have their own independent entries (users can directly access an atomic service by a touch, tap, or scanning code) and are installation free (users can access an atomic service after it is installed by the system program framework in the background). Atomic Services can provide multiple convenient services for users.
- Added local emulators for Phone devices (coming soon).
- Added the Super device (still in experimental phrase), with support for the Phone+Phone and Phone+Tablet device networking modes, allowing you to debug distributed apps, for example apps with services transferable between devices. For details, see [Running Your App on the Super Device](https://developer.harmonyos.com/en/docs/documentation/doc-guides/run_simulator-0000001053303709#EN-US_TOPIC_0000001108146028__section78884111389 "Running Your App on the Super Device").
- Added support for app development for Router devices, allowing you to quickly develop router apps using the provided templates.
- Added support for importing HarmonyOS sample projects. By interconnecting with open-source communities of OpenHarmony, you can directly read sample data from Gitee and create sample projects in one-click mode.
#### Enhanced Features
- Updated the HarmonyOS SDK to version 2.1.1.21 (Stage: Release). Optimized the download process of HarmonyOS SDK: When you are installing DevEco Studio for the first time, Java SDK, JS SDK, Toolchains and Previewer are downloaded at the same time by default.
- Improved the app signing capability:
- Added support for automatic app signing.
- Added support for storing app signature information via configuring files.
- Enhanced the Java editor capabilities by integrating the HuaweiCloud SmartAssist to provide the intelligent code completion capability.
- Enhanced the preview capabilities. Update the HarmonyOS SDK to the latest version to try out the enhanced features.
- Added support for previewing the XML files in the qualifiers sub-directories.
- Optimized the image transmission and real-time preview performance of the previewer.
- Improved the Service Widget development function, allowing you to develop service widgets for Wearable devices, with multiple templates available.
- Optimized the compilation and building performance to improve the compilation and building speed of the HAPs and apps.
- Added support for constructing and using C++ shared libraries to HAR packages.
- Optimized the display of the HiLog output and added support for result filtering.
#### Solved Issues
- Fixed an issue where automatic association was not available for the shape and vector in the graphic directory.
- Fixed an issue where the entry and feature modules could not reference HAR resources at multiple levels.
- Fixed an issue where the WebView components could not be displayed on the emulator.
- Fixed an issue where C/C++ project templates were not available for Phone devices.
- Fixed an issue where the previewer could not switch between landscape and portrait modes.
- Fixed an issue where the previewer would not support languages other than Chinese and English.

