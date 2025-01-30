# Terms-and-definitions-Appium

I found a lot of definitions and terms about Selenium Webdriver, TestNG and Appium on the Internet, but not all of them were understandable to me as a beginner. It took a time to find ones that would be explained simply and clearly. Therefore, I created this repository to have all the definitions in one place so that I could check them if necessary. The definitions are not mine, they were all found on the Internet.
______________________________________________________________________________________________________________________________________________________________________________________

## Terms and definitions of Appium

### 1. Appium definition
   
Appium is an open-source, cross-platform automation tool for testing mobile applications. It allows developers to automate the testing of both Android and iOS apps. Appium supports native, hybrid, and mobile web applications, and it is designed to be platform-agnostic, which means that the same test scripts can be used across multiple platforms.

### 2. Main differences between Appium and Selenium Webdriver

  - Appium is designed for automating mobile applications (both Android and iOS), while Selenium WebDriver is primarily used for automating web browsers;

  - Appium requires a server to interact with mobile devices, while Selenium directly interacts with web browsers;

  - Appium requires a mobile device or emulator/simulator to run tests, whereas Selenium WebDriver only requires a web browser for test execution;

  - Appium allows for gestures and touch actions (like swipe, pinch, and scroll) on mobile devices, whereas Selenium focuses on mouse and keyboard actions in web browsers;

  - Appium requires the use of specific mobile drivers (like UiAutomator for Android or XCUITest for iOS) to interact with mobile apps, while Selenium uses browser drivers (like 
    ChromeDriver or GeckoDriver) to interact with web browsers;

  - Another difference is that Appium requires the installation of mobile development tools like Android SDK or Xcode to interact with mobile devices, while Selenium only requires the 
    installation of a web driver for browser automation.

### 3. Tools and steps to install Appium

3.1. Install Appium: Download and install Appium on your computer. Appium can be installed directly from the Appium website.

3.2. Install SDKs and JDKs: Appium requires the software development kit (SDK) of the mobile platform you want to test on. For example, if you want to test an Android app, you must install the Android SDK. You must also install the Java Development Kit (JDK) for running Appium.

3.3. Install and configure IDE: Choose an Integrated Development Environment (IDE) for writing test scripts, such as Eclipse or IntelliJ IDEA.

3.4. Set up environment variables: After installing the SDKs and JDK, set up the environment variables so that Appium can locate them. For example, set the PATH variable to the location of the SDKs and JDK.

3.5. Connect a device or emulator: Connect a physical device or launch an emulator to test on. For Android, use Android Debug Bridge (ADB) to connect the device or emulator to Appium. For iOS, use the Xcode developer tools.

3.6. Install UiAutomator2 Driver. In Appium, UIAutomator2 is used as a driver to interact with and automate Android devices.

3.7. Start Appium server: Start the Appium server by running the Appium executable or using a package manager. The Appium server listens for incoming commands from the test script and translates them into actions on the device or emulator.




I will keep adding information....
