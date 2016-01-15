# Automated Tests for Telerik Academy System

***

## Notes

* **KendoGrid view** paging and sorting - Write separate tests in every page

* **KendoGrid Extensions** - KendoGrid class is slower than just using javascript and is less readable

* In **Facade** shoud stay operations that combine several pages. Methods in Page are service methods whichare ok to be there and not to wrap them in the facade. The facade should be used when we have very big workflow (around 10 steps) - for example login page, the main page and then successfull page for validation.

## Deadline 15.01.2016

* Extract **Owner** in constants (in QA.TelerikAcademy.Core)

* Add attribute for connection between given test from VS and test case (for example: [TestCaseId(1234)])

* Extensions for browser should be in **Core** project, not in **BaseFacade** (The facade should hold functionalities only)

* Separate tasks to cover the **high priority test cases**

# In **Status Report**

* How much automated tests by priority 

* Who and how much tests has made (for every week and total)

* Create table with the **modules** and their corresponding - **test cases**(by priority - how much high, medium and low), **tests**(how much automated/manual and how much are passed/failed), bugs(how much are reported)
