# Overview

Automation test for API

<h3> Prerequisites</h3>

* JAVA JDK
* IntelliJ IDEA 
* Maven (IntelliJ plugin)
* Cucumber for Java (IntelliJ plugin)
* Gherkin (IntelliJ plugin)
* CheckStyle (IntelliJ plugin)
 <h3>Execute test by commandline: </h3>
 
- Run test all feature with environment (for api for now) : mvn clean verify -pl=api -Denvironment=dev
- Run test command with environment and tag name : mvn clean verify -pl=api -Denvironment=dev -Dtags="@Post"

<h3>Execute test by IntelliJ: </h3>

    - Right-click `play` icon on a feature file or scenario we need to execute them
    
    - Choose option `Modify Run Configuration`
    
    - Input environment. E.g: `-Denvironment=dev`
    
    - Click `OK` to save that settings
    
    - **Remember that just do it once except we need to change testing environment or execute other tests**
    
    - Next step: Just click the 'play' icon to execute your the tests

<h3>Create test cases </h3>

* Open src\test\resources\features 
* Create "Gherkin" files for each task
