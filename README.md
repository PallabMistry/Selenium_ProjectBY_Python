# Selenium_ProjectBY_Python
Selenium’s Python Module is built to perform automated testing with Python. Selenium in Python bindings provides a simple API to write functional/acceptance tests using Selenium WebDriver. 

Combined with Python, Selenium offers a powerful and easy-to-learn toolset for automating browser interactions. Python’s simple syntax makes it ideal for quickly writing clear and maintainable test scripts.

Set all environments, webdriver, etc.
Install manager:

```pip install webdriver-manager```

Using Chrome -
```js
from selenium import webdriver
from selenium.webdriver.chrome.service import Service as ChromeService
from webdriver_manager.chrome import ChromeDriverManager

driver = webdriver.Chrome(service=ChromeService(ChromeDriverManager().install()))
```

Using FireFOx -

```js
from selenium import webdriver
from selenium.webdriver.firefox.service import Service as FirefoxService
from webdriver_manager.firefox import GeckoDriverManager

driver = webdriver.Firefox(service=FirefoxService(GeckoDriverManager().install()))
```

