# maven-babysteps
a random application to get the hang with Java and maven. And maybe we will see some cool agent action going on here with the JADE or the JIAC framework.

## MySteps

* go to https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
* and go to https://maven.apache.org/guides/getting-started/index.html

* Execute the initial code. It took quite some time. My network connection was not persistent at the time.
 * `mvn archetype:generate -DgroupId=de.tum.lvt.maven -DartifactId=maven-babysteps -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`
* Now lets go to our project and see the unit tests
 * `cd marven-babysteps`
 * `mvn test`
 * nice, they are rock solid.
* Build it
 * `mvn package`
* Now lets try to execute. But we want nice autocompletion in Windows therefore we use the powershell:
 * `powershell`
 * `javac

