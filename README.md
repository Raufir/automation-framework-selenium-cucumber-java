# Selenium Cucumber Java Automation Framework


This framework is ready to use for UI automated test using selenium webdriver.

## Prerequisite

- Ensure JDK-17 is installed and JAVA_HOME is written in system variables with correct path.
- Ensure Maven is installed, M2_HOME and MAVEN_HOME is written in system variables with correct path.
- Ensure homebrew is installed if you are using macOS

## Installation Steps

To use this framework:
1. Fork the repository.
2. Clone: Download your copy of the repository to your local machine using

`git clone https://github.com/Raufir/automation-framework-selenium-cucumber-java.git`

3. Import this project in [IntelliJ IDEA](https://www.jetbrains.com/idea/download/).

## Languages and Frameworks



- Java 11:  as the programming language
- Selenium Webdriver: as the web browser automation framework using the Java binding
- WebDriverManager: as the browser driver management library
- TestNG: as the testing framework
- IntelliJ IDEA: as the IDE

## Getting Started (Windows)

- Once the cloning is successful, download [Chromedriver](https://chromedriver.chromium.org/downloads) and [Geckodriver](https://github.com/mozilla/geckodriver/releases) compatible with your windows machine.
- Extract the zipped folders.
- Move those extracted files to **src> main > java > Driver > drivers**
- Open the project with IntelliJ IDEA.
- Go to test > runners > MainRunner.java
- On line 20, click on the Play button and select `Run 'MainRunner'`

That's it your project should be up and running by now in your windows machine!

## Getting Started (MacOS)

- Once the cloning is successful, download [Chromedriver](https://chromedriver.chromium.org/downloads) and [Geckodriver](https://github.com/mozilla/geckodriver/releases) compatible with your macOS machine.
- Extract the zipped folders.
- Move those extracted files to **src> main > java > Driver > drivers** (Ensure these aren't exe files!)
- Open the project with IntelliJ IDEA.
- Notice that under drivers folder, both of these drivers are showing in red color - Don't panic!
- Open terminal and run this ```brew install --cask chromedriver```.
- Open terminal and run this ``` brew install geckodriver```.
- Open the **DriverFactory.java** file, and **remove** this code from line 29 ```System.setProperty("webdriver.chrome.driver", System.getProperty("user.dir") + "/src/main/java/Driver/drivers/chromedriver.exe");```
- On the **DriverFactory.java** file, **remove** this code from line 37 ```System.setProperty("webdriver.gecko.driver", System.getProperty("user.dir") + "/src/main/java/Driver/drivers/geckodriver.exe");```
- Go to test > runners > MainRunner.java
- On line 20, click on the Play button and select `Run 'MainRunner'`

That's it your project should be up and running by now in your macOS machine!