# _Session 1:_
In our session 1, we covered the basic topics related to TestNG framework. Here is a summary of what we discussed:
- Introduction to TestNG: We discussed what TestNG is and how it is used for testing software applications.
- Overview of TestNG: We covered the features of TestNG and how it can be used to write powerful and flexible tests.
- Advantages of using TestNG: We discussed the benefits of using TestNG for testing, such as its support for various annotations, test grouping, and parallel test execution.
- Installing TestNG: We explained how to install TestNG in Eclipse IDE and how to configure it for use in test automation projects.
- TestNG Annotations: We went over the various annotations in TestNG such as @BeforeSuite, @BeforeTest, @BeforeClass, @BeforeMethod, @AfterMethod, @AfterClass, @AfterTest, and @AfterSuite.
- TestNG Annotations benefits: We discussed the advantages of using TestNG annotations, such as providing a clear and organized structure to test cases and enabling easy -configuration of test execution.
- TestNG Test and TestNG.xml: We explained how to create and run TestNG tests using the TestNG.xml file, which contains information about the tests to be executed and their configurations.
- Structure of TestNG.xml: We provided an overview of the structure of the TestNG.xml file, which includes information about the test suites, test cases, and their respective parameters and configurations.
Overall, we covered a wide range of topics related to TestNG, from its installation and setup to the use of annotations and the creation of test suites with the TestNG.xml file.


# _Session 2:_
In our session 2, we covered several advanced topics related to TestNG framework. Here is a summary of what we discussed:
- Execution Order of TestNG Annotations: We learned about the order in which TestNG executes the various annotations, such as @BeforeSuite, @BeforeTest, @BeforeClass, @BeforeMethod, @Test, @AfterMethod, @AfterClass, @AfterTest, and @AfterSuite.
- Priority in TestNG: We discussed how to use the @Test(priority) annotation to set the priority of test cases and specify the order in which they should be executed.
Including and Excluding TestNG test cases: We learned how to use the <include> and <exclude> tags in the TestNG XML file to include or exclude specific test cases.
- Running test cases with Regex: We discussed how to use regular expressions to run test cases that match a specific pattern.
- Ignore Test Cases in TestNG: We learned how to use the @Ignore annotation to skip specific test cases that are not ready or not necessary to be executed.
- Skip Test Cases in TestNG: We discussed how to use the throw keyword to skip a test case at runtime and how to use the dependsOnMethods attribute to skip a test case if a dependent test case fails.
- Groups in TestNG: We learned how to group test cases using the @Test(groups) annotation and execute them based on the specified group.
- Dependencies in TestNG: We discussed how to use the dependsOnGroups and dependsOnMethods attributes to specify dependencies between test cases.
- Exceptions in TestNG: We learned how to handle exceptions in TestNG using the expectedExceptions and expectedExceptionsMessageRegExp attributes. We also discussed how to use the @Test(expectedExceptions) annotation to catch specific exceptions in test cases.
  
  
  # _Session 3:_

- We started by discussing TestNG listeners and how they can be used to perform actions before or after a test case or suite. Then, we moved on to explore the different parameters that can be used in TestNG and how they affect the behavior of the test cases.
- Next, we talked about data providers in TestNG and how they can be used to provide test data to test cases. We also discussed parallel execution in TestNG and how it can be used to speed up test execution.
- After that, we delved into assertions in TestNG and the different types of assert statements that can be used to verify expected results. We also talked about IRetryAnalyser in TestNG, which can be used to retry failed test cases.
- Moving on, we explored TestNG reports and how they can be generated to provide detailed information about the test execution. Finally, we discussed re-running failed test cases using failedTestng.xml and how it can be used to rerun only the failed test cases.
Overall, our discussions covered a wide range of topics related to TestNG and how it can be used to write efficient and reliable automated test cases.
