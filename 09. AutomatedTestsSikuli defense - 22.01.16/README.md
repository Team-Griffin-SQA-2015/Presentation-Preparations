# Automated Tests for Telerik Academy System with Sikuli

***

## Notes

* Check Sikuli license

* Use OS path join for quotes

# Fixed issues after code review by Tsvetomir Todorov:

* Add all html reports to gitignore
* sys.path.append(bdLibPath) should be on new line
* Extract in separate function: sleep(2) for i in range(1,2): type(Key.DOWN)
* Use assert instead of self.assertTrue they are the same
* The test should finish with an assertion
* The test should finish with an assertion
* Endless loop? Add timeout or attempts as a function parameter
* The test should finish with an assertion
* Skip Verify in the test name. Also, consider to cut down the testname

## Deadline 22.01.2016

Write automated ui tests with Sikuli.