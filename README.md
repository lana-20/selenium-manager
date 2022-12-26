# Selenium Manager - a new way to config/setup driver environment


- Make test automation more elegant and robust
- Run Selenium in a working out-of-the-box environment
- Simplify environment setup and configuration
- Beefed up 'Selenium with Batteries'


![image](https://user-images.githubusercontent.com/70295997/209493750-4e6a66fe-39f4-40b3-89ba-95f7aff807e6.png)

Configuring browser drivers has been for many years a task which users need to perform in order to have a working environment to run Selenium.

Setting up a browser driver once is not that complicated, but as browser release cycles got shorter, and now we have a __new Chrome/Firefox/Edge version every 4-6 weeks__, the task of __keeping the browser driver in sync with the browser version__ is not that easy anymore.

Selenium Manager is a new tool that helps to get a working environment to run Selenium out of the box. Beta 1 of Selenium Manager will __configure the browser drivers for Chrome, Firefox, and Edge if they are not present on the PATH__.

To run a Selenium test with Selenium 4.6, you only need to have Chrome, Firefox, or Edge installed. If you already have browser drivers installed, this feature will be ignored.

Future releases of Selenium Manager will eventually even __download browsers__ if necessary.

...


---
[Introducing Selenium Manager - Built-in Driver Manager](https://www.selenium.dev/blog/2022/introducing-selenium-manager/)

[Selenium Manager Binaries Repo](https://github.com/SeleniumHQ/selenium/tree/trunk/common/manager)

[Selenium Manager 4.6.0 - No Need To Setup Any .exe File || No System Property || No WebDriverManager](https://youtu.be/M3RyBvUTOpk)

[WebDriverManager: No Need to write WebDriver driver = new ChromeDriver();](https://youtu.be/kqQd6PlQtcs)

[Sergey Pirogov's Webdriver Manager for Python - 3rd-Party Library](https://pypi.org/project/webdriver-manager/)

[Boni Garcia's Webdriver Manager for Java - 3rd-Party Library](https://bonigarcia.dev/webdrivermanager/)
