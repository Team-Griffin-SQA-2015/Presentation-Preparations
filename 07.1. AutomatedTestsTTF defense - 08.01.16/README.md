# Automated Tests for Telerik Academy System

***

## Deadline 08.01.2016


* Provide automated tests for TALS with **Teleri Testing Framework (TTF)**.
	* At least **20 tests** per team member

* Set **Category** to tests by module and by priority

* Test case **automation**

* After new build (new version)- **retest**

* **Report**

## Notes from stakeholders

* Bug and test cases relation
How many test cases are infected of given bug report

* Attributes of tests (Custom)
	* [**TestMethod**]
	* [**Priority**(Priorities.High]
	* [**TestCategory**(Categories.PurchasingCenter)]
	* [**TestCategory**(Categories.ContiniusIntegration)]
	* [**ManualTestCase**(12330)]
	* [**Owner**(Owners.AntonAngelov)]
	* [**ScreenshotOnFail**(true)]
	* [**VideoRecording**(VideoRecordingMode.OnyFail)]
	* [**ExecutionEngineAttribute**(Browsers.Firefox)]

* Don't use **random** data - make a **factory**

* Logger
For example NLogger
