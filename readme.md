Hello, 😃
This is how we setup selenium webdriver for Firefox browser using Python.




when we try to implement the python code from the [Selenium python read docs](https://selenium-python.readthedocs.io/getting-started.html)





you may get this error: InvalidArgumentException: Message: binary is not a Firefox executable error in Python linuxmint environment

The reason behind this error is we are not mentoning(read the below docs to know GeckoDriver) the firefox Driver.

Selenium Firefox Driver, also called GeckoDriver, is a browser rendering engine developed by Mozilla for many applications. It provides a link between test cases and the Firefox browser. Without the help of GeckoDriver, one cannot instantiate the object of the Firefox browser and perform automated Selenium testing.


Ubuntu 22.O + user's dont need to install the geckodriver, Which had been installed while we install(/snap) firefox.


Note: You can check the path of a application using the 'which' command
eg : 
$ which firefox
>>/usr/bin/firefox



