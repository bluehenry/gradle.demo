# gradle.demo
[Gradle](https://gradle.org/) is a build tool. Write in Java, C++, Python or your language of choice. Package for deployment on any platform. Go monorepo or multi-repo. And rely on Gradle's unparalleled versatility to build it all.


# [Installation](https://gradle.org/install/)
Install on macOS
```bash
brew install gradle
gradle -v
```
# [Creating New Gradle Builds](https://guides.gradle.org/creating-new-gradle-builds/)

## Init project
```bash
gradle init
```
* Select type of project to generate: 8 kotlin-application
* Select build scripts DSL(Domain Specific Language): 2 kotlin  

## Run
```
./gradlew tasks run
```

## Upgrade with the Gradle Wrapper
```bash
./gradlew wrapper --gradle-version=6.2.2 --distribution-type=bin
```
