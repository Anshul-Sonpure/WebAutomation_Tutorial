## _Summary of Selenium Topics Covered_
Throughout these 6 sessions, we have covered a wide range of topics related to Selenium. We have started with the basics of Selenium WebDriver and then moved on to more advanced topics such as handling checkboxes, radio buttons, dropdowns, web tables, and alerts. We have also discussed how to handle SSL certificates, take screenshots, and switch to iframes using Selenium WebDriver. Additionally, we have covered the usage of Apache POI to read and write data from Excel files in Selenium code.
Furthermore, we have explored the usage of the JavascriptExecutor interface in Selenium, which allows executing JavaScript code directly in the browser. Finally, we have discussed setting up and using Selenium Grid to perform parallel testing.
Overall, we have tried to cover most of the important topics in Selenium that are required to create and execute robust test automation scripts.

### _Summary of Session-1_,
- We started by discussing the definition of locators, which are used in Selenium to locate web elements on a page. We covered the different types of locators available in Selenium, including ID, name, class name, tag name, link text, and CSS selectors.
- We also talked about the Same Origin Policy and how to set up Selenium WebDriver in Eclipse, and wrote a basic Selenium test script.
- Overall, we learned how automation testing with Selenium can improve test coverage and reduce costs.


### _Summary of Session-2_,
- We started by discussing the definition of locators, which are used in Selenium to locate web elements on a page. We covered the different types of locators available in Selenium, including ID, name, class name, tag name, link text, and CSS selectors.
- We then talked about best practices for selecting a locator, such as using unique and stable locators, avoiding using dynamic values, and prioritizing readability and maintainability.We demonstrated how to locate web elements using different types of locators, using examples such as finding an element by ID or by class name.
- We discussed the preferred sequence for locators in Selenium, which generally starts with ID, followed by name, class name, and so on, depending on the context and uniqueness of the web element.We explained the difference between Find Element and FindElements in Selenium WebDriver. Find Element returns a single web element that matches the specified locator, while FindElements returns a list of web elements that match the locator.
- Finally, we covered some of the commonly used Selenium WebDriver commands, such as click(), sendKeys(), getText(), and getTitle(). We demonstrated how to use these commands to interact with web elements and retrieve information from web pages.

### _Summary of Session-3_,
- We started by discussing XPath in Selenium, which is used to locate web elements on a page using XML path expressions. We covered the different types of XPath expressions, how to write them, and the concept of independent and dependent XPath.We then talked about synchronization in Selenium, which is used to ensure that the web driver waits for a web element to load before attempting to interact with it. We demonstrated how to use common expected conditions in explicit wait, such as presenceOfElementLocated and visibilityOfElementLocated.
- We discussed about pageLoadTimeout and scriptTimeout in Selenium, which are used to set the maximum time allowed for a web page to load and for a script to execute, respectively. We also covered FluentWait in Selenium, which is a more flexible way to implement synchronization.We discussed exceptions in WebDriver, which are thrown when something goes wrong during the execution of a test script. We covered some of the commonly encountered exceptions, such as ElementNotVisibleException and NoSuchElementException, and demonstrated how to handle them using try-catch blocks.
- We discussed about Chrome Options & Desired Capabilities in Selenium WebDriver, which are used to customize the behavior of the Chrome browser during test automation. We demonstrated how to set options such as headless mode and disable-infobars.Finally, we covered how to handle cookies in Selenium WebDriver, which is used to manage user sessions and authentication. We demonstrated how to add, delete, and retrieve cookies using WebDriver commands.

### _Summary of Session-4_,
- We discussed the differences between Selenium 3 and Selenium 4. We looked at the changes in the architecture, capabilities, and the utility methods for finding elements in Java. We also talked about the modifications made to the Actions class, waits and timeout features, and the new features introduced in Selenium 4.
- We also talked about one of the significant changes in Selenium 4 is the introduction of Object Location and Relative Locators. These features allow you to locate elements easily and perform actions on them. Additionally, we talked about Chrome Dev tools, which can be used to debug and inspect web pages.
- Another topic we covered was the capture screenshot of specific web element. With Selenium 4, you can take screenshots of specific web elements rather than the entire page. We also discussed how to open a new tab or window in the browser using Selenium 4.

### _Summary of Session-5_,
- Working with checkboxes and radio buttons: We learned how to locate and interact with checkboxes and radio buttons using Selenium.
- Handling images: We explored how to locate and interact with images on a webpage using Selenium.
- Action class: We discussed the use of the Action class in Selenium to perform complex actions on a webpage, such as click-and-hold or drag-and-drop.
- Select class: We covered how to use the Select class in Selenium to handle dropdowns and select options from them.
- Robot class: We learned about the Robot class in Selenium, which can be used to simulate keyboard and mouse events on a webpage.
- Alert in Selenium: We covered how to handle alerts and pop-ups using Selenium.
- Handling web tables: We explored how to locate and interact with web tables on a webpage using Selenium.
Overall, our sessions aimed to provide a comprehensive understanding of Selenium and its various capabilities, enabling learners to effectively automate web testing tasks.

### _Summary of Session-6_,
- Apache POI in Selenium: We discussed how to use the Apache POI library to read and write data to Excel files in Selenium code.
- JavascriptExecutor in Selenium: We explained how to use the JavascriptExecutor interface to execute Javascript code on a web page using Selenium WebDriver.
- Take Screenshot in Selenium WebDriver: We explored how to capture screenshots of web pages in Selenium code using the TakesScreenshot interface.
- Handle iframe in Selenium: We learned how to handle iframes (or inline frames) in Selenium WebDriver by switching to and from them using the switchTo() method.
- Handle SSL Certificate in Selenium: We discussed how to handle SSL certificate errors in Selenium code.
- Selenium Grid: We covered the basics of Selenium Grid and how to set it up for distributed testing.
