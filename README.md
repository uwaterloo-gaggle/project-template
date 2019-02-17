# Project Template
You are on your way to creating a new gaggle project! A few more steps remain:

1. Edit `settings.gradle`, replacing `{YOUR PROJECT NAME}` with your project name
2. Replace this README with one tailored to your project

## Building your project
- MacOS/Linux/UNIX: `./gradlew build`
- Windows: `gradlew.bat build`

## Application modules
If you have a large project, it is recommended to split your project into modules.

This template already contains one module by default, called `main`, containing 3 "Hello World" programs written in Java, Kotlin and Scala.

For single-module projects, all code should be placed in this `main` module. Project dependencies should be placed in `main/build.gradle`.
