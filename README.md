# Command-Line-Tools for LabVIEW
This LabVIEW addon contains utilties to make running unit tests and builds easy with Jenkins or other CI/CD system.

There are 4 primary functions:
1. Execute LabVIEW build spec
2. Build VIPM package
3. Execute NI Unit Test Framework tests and generate JUnit XML results
4. Execute JKI VI Tester tests and generate JUnit XML results

There are several dependencies:
1. LabVIEW 2014 or greater - This is due to the build API to Get/Set build spec version. The build number from the build system will be injected as the last number in the build version.
2. [LabIVEW-CLI](https://github.com/JamesMc86/LabVIEW-CLI) - Both C# application and unpublished LabVIEW library
3. [JKI VI Tester](https://github.com/JKISoftware/JKI-VI-Tester)
4. [JKI VI Testser JUnit XML Test Results](https://github.com/JKISoftware/JKI-VI-Tester-JUnit-XML-Test-Results)
5. [NI Unit Test Framework](https://ni.com)
6. [UTF Junit Report](https://github.com/LabVIEW-DCAF/UTF-Test) - Unpublished library
7. [Junit Results API](https://github.com/NISystemsEngineering/LV-JUnit) - Unpublished library
8. [Jenkins JUnit Plugin](https://wiki.jenkins-ci.org/display/JENKINS/JUnit+Plugin) - if using Jenkins
