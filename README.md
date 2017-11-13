# MavenScala
Scala maven boilerplate

Adds only the Scala lang libraries.

None of the pre-existing mvn archetypes worked well for me, so creating this. Feel free to fork for usage.

Make sure you do the following.

- `git clone` this repo
- Delete .git and the sub folders. Obviously you wont be needing the commit history.
- `git init` if needed
- Install maven for your platform/operating system
- `mvn clean install`
- If you open the project in Intellij, then it would ask if this can be added as a Maven project. Select Yes and then proceed.
- Setup up Scala SDK. If you are using Intellij, it should prompt for setting up the Scala SDK. The previous step should have installed Scala SDK 2.12.3 through maven.
- Setup Java SDK
- You should be able to run the Runner.scala without any issues

