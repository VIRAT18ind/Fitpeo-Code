# Fitpeo-Code
Assignment Test Cases provided by  FitPeo


Instructions to create the file in eclipse
Steps to Create a Selenium Project in Eclipse:
1. Install Java and Eclipse
Java: Ensure Java Development Kit (JDK) is installed.
Verify by running: java -version in the command prompt.
Download JDK: Oracle JDK
Download latest JDK
Navigate to Java Downloads Oracle in the browser
In the website under the Downloads > Select Windows > x64 MSI Installer or x64 Installer
Extract the file and finish the stepup to install 
Verify by running: java -version in the new command prompt.
2.Eclipse: Download Eclipse IDE for Java Developers.
Download: Eclipse Downloads
3. Set Up a New Java Project in Eclipse
Open Eclipse and select a workspace.
Create a New Project:
Go to File > New > Java Project.
Enter a project name (e.g., SeleniumDemo).
Choose JRE version which is installed prefered JRE JavaSE-1.8 or your current downloaded jdk version 
Click Finish.
4. Add Selenium WebDriver to Your Project
Download Selenium JAR files:
Visit:  Downloads in Selenium.dev
Go to Java download the lastest version
After downloading extract the files
Now again go back to the website click on downloads
Scroll down till platforms supported by selenium
Expand the Browsers option
Choose Firefox
click on documentation
click on gecko driver releases
Choose the release version based on your browser version(its is avaible in about section of your browser)
Scroll down till assets
Choose winx32 or winx64.zip file based on your system supporting
Download the latest version of Selenium WebDriver and its dependencies (usually a .zip file).
Extract the files in a folder in desktop
Add JAR Files to Eclipse:
Jar files are present in the extracted java folder
Right-click on your project > Properties > Java Build Path.
Click Libraries > CLick on Modulepath >CLick on Add External Jars
Go to extracted java folder 
Select all downloaded Selenium JARs and click Open.
Click Apply and Close.
6. Create a New Package and Class
Create Package:
Right-click src > New > Package.
Enter a package name (e.g., seleniumTests).
Create Class:
Right-click on the package > New > Class.
Enter a class name (e.g., FirstTest).
Check public static void main(String[] args) and click Finish.
7.Go to downloads in file exploer
Extract the firefox webdriver
Copy the Path of .exe file and paste it in the place of Value in the code
i.e System.setProperty("webdriver.gecko.driver","./Softwares/geckodriver.exe"); in place of ./Softwares/geckodriver.exe paste the copied Path
