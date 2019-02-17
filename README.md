# Project Template
You are on your way to creating a new gaggle project! A few more steps remain:

1. Edit `settings.gradle`, replacing `{YOUR PROJECT NAME}` with your project name
2. Replace this README with one tailored to your project

## Building your project
- MacOS/Linux/UNIX: `./gradlew build`
- Windows: `gradlew.bat build`

## Importing your project into Intellij
1. Open the project folder using the IDE.
2. Wait for a small popup to appear in the bottom-right of your screen, then click on "Import Gradle project".
   ![Gradle configuration popup](https://user-images.githubusercontent.com/9571936/52910004-26751500-325f-11e9-97bb-5c7bfbb15f15.png)
3. In the window that appears, change the settings so your configuration matches the configuration depicted in the red box below.
   ![Gradle configuration image](https://user-images.githubusercontent.com/9571936/52909988-ff1e4800-325e-11e9-94a9-e69cf5644de2.png)
4. Click "Ok".

### Producting a "fat jar"
Use the commands below to produce a single JAR containing both your program code an it's dependencies:
- MacOS/Linux/UNIX: `./gradlew main:fatJar`
- Windows: `gradlew.bat main:fatJar`

**This is the command to run when packaging your program for execution on Spark**

## Application modules
If you have a large project, it is recommended to split your project into modules.

This template already contains one module by default, called `main`, containing 3 "Hello World" programs written in Java, Kotlin and Scala.

For single-module projects, all code should be placed in this `main` module. Project dependencies should be placed in `main/build.gradle`.
