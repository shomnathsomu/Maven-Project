# Maven - Project/Build Management tool

### Importance of Maven
1. Central repository to get dependencies
2. Maintaining common structure across the organization
3. Flexibility in integrating with CI tools
4. Plugins for test framework execution

### Maven Install
1. Download the Binary zip archive from https://maven.apache.org/download.cgi
2. Edit the system environment variables
3. Create a new System variables; Variable name: MAVEN_HOME and Variable value: maven folder path in the local drive
4. Click on the Path of System variable and edit and create a new Environment variable copying the maven binary folder path in the local drive
5. Go to the Command Prompt and check maven version: mvn --version

### POM.xml
1. Maven Surefire Plugin: The Surefire Plugin is used during the test phase of the build lifecycle to execute the unit tests of an application. It generates reports in two different file formats:
* Plain text files (*.txt)
* XML files (*.xml)
By default, these files are generated in ${basedir}/target/surefire-reports/TEST-*.xml.

2. Maven Selenium Java: Selenium provides support for the automation of web browsers. It provides extensions to emulate user interaction with browsers, a distribution server for scaling browser allocation, and the infrastructure for implementations of the W3C WebDriver specification.

3. Maven TestNG: TestNG is a testing framework inspired from JUnit and NUnit but introducing some new functionalities that make it more powerful and easier to use. It supports test configured by annotations, data-driven testing, parametric tests, etc.

4. Maven REST Assured: Java DSL for easy testing of REST services

## Maven Run
1. Open the command prompt in the maven project directory
2. Type [mvn clean] and hit ENTER.
3. Type [mvn compile] and hit ENTER.
4. Type [mvn test] and hit ENTER.
