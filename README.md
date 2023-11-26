# build-tools
Create Ant+Ivy , Maven and Gradle build scripts to build the project
Building and Testing:


Maven:
To build the project and create artifacts using Maven, follow these steps:

Install Maven if you haven't already.
Open a terminal and navigate to the project directory.
Run the following command:
mvn clean install



Gradle
To build the project and create artifacts using Gradle, follow these steps:

Open a terminal and navigate to the project directory.
Run the following command (on Unix-like systems):
./gradlew clean build
On Windows, run:
gradlew.bat clean build



Running Tests:
To run tests separately, use the following commands:


Maven
mvn test


Gradle
./gradlew test    # Unix-like systems
gradlew.bat test  # Windows
