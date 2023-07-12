# Selenium Cucumber Java Automation Framework


This framework is ready to use for UI automated test using selenium webdriver.

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

## Getting Started

- Once the cloning is successful, download [Chromedriver](https://chromedriver.chromium.org/downloads) and [Geckodriver](https://github.com/mozilla/geckodriver/releases) compatible with your machine.
- Unzip the zipped files.
- Move those files to **src> main > java > Driver > drivers**
- Open the project with IntelliJ IDEA.
- Open the DriverFactory class and notice line 36 and 43
- On Windows machine: ensure they are written as `chromedriver.exe` and `geckodriver.exe`. On Mac machine: they are written as
- Go to test > runners > MainRunner.java
- On line 20, click on the Play button and select `Run 'MainRunner'`