# MuleMule
MuleSoft project
API-led connectivity approach

A framework that combines microservices architecture with a holistic API strategy to connect through well-defined layers, 
different types of pupose-built, resuable APIs designed with the consumption of data top of mind.

3 types of APIs
1. system APIs - provide us an access to the underlying core systems of record and expose data. (exposes backend database without business logic)
2. Process APIs - Typically, allow us to compose, transform, enrich, aggregate and orchestrate data as needed.
3. Experience APIs - Allow us to ease reconfigure data according to specific needs of the end user

What are the benefits of API-led aonnectivity?
01 Assests as APIs - use of APis to provide both a consumable and controlled means of accessing systems or applications
02 APIs are resuable and designed to be easily changes abd consumed across multiple applications
03 Faster development -APIs are resusable and designed to be easily changed and consumed across multiple applications
04 Improve governance - with APIS we can provide access to data and business logic in a governed and secured form
05 Transition to cloud- Speed up the transition of legacy systems to a cloud infrastructure easily and helps to innovate faster

Why should I invest time in learning Mulesoft
1. API growth rate https://techbeacon.com/app-dev-testing/3-ways-apis-help-developers-deliver-software-faster
2. MuleSoft is a market leader - for enterprise integration, for full  Lifecycle API Management
3. return on investment

Learning map
install development tools -> create the project zero -> HTTP connectors->DataWeave Language, Variable properties Files ->VM connectors
->Database Connectors ->File connectors ->Error Handling ->Anypoint platform designer (Design Center), Deploy API -> Test using Postman

How to get most out of the courses
1. watch or read over and over again until you understand it!
2. Hands on approach, do excercises
3. Ask questions
4. use MuleSoft documentation
5. Use Google

Installation 
1. install java 8
 create %JAVA_HOME%\bin to point the jdk, echo %JAVA_HOME%, echo %PATH%
  
 >java -version
        java version "11.0.9" 2020-10-20 LTS
        Java(TM) SE Runtime Environment 18.9 (build 11.0.9+7-LTS)
        Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.9+7-LTS, mixed 

2. Install Maven
    %MAVEN_HOME%\bin %M2_HOME%\bin
    echo %MAVEN_HOME
    echo %M2_HOME%

    >mvn -v
        Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
        Maven home: C:\ProgramData\chocolatey\lib\maven\apache-maven-3.6.3\bin\..
        Java version: 1.8.0_192, vendor: Oracle Corporation, runtime: C:\Program Files\AdoptOpenJDK\jdk8u192-b12\jre
        Default locale: en_NZ, platform encoding: Cp1252
        OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

3. install Git choco install git -y
   >git --version
        git version 2.35.1.windows.2

4. install postman choco install postman -y
5. Install MariaDB (free opensource db) - for testing puposes
   https://www.mariadbtutorial.com/getting-started/install-mariadb/
   msi is downloaded.
   set root password
   TCP port 3306
   Find the MariaDB tools in the startup Menu
 ![alt text](Mariadb.png)
   

    Also can be accessed by GUI HeidiSQL
    ![alt text](Heidi.png)
    ![alt text](Heidi2.png)

6. find the .exe in D:\Devtools\AnypointStudio\AnypointStudio.exe
   workspace: D:\Projects_Mule\MuleMule\AnypointStudio\studio-workspace

7. Create the first Mulesoft project
File>new>Mule Project > (create project name 1.Project_zero)
</br>two dependencies and Mule runtime engine
![alt text](dependencies.png)

"1.Project_zero.xml@
Editor is devided into 3 different sections: Message flow (visual representions), Global elements (connections), configuration xml (xml represnetion)
Mule palette - connectors and processors
Mule properties view changes according to the connectors dragged into the editor.
window>show view>console



