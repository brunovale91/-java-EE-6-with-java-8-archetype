# java-EE-6-with-java-8-archetype

ThisMaven archtype can be used to create new Java EE 6 projects with java 8.
Archetype groupId, artifactId and version can be found in the pom.xml of this project.

Steps to create a Java EE 6 project from this archetype:

  - Clone this repository to your computer
  - To install this archetype in your local maven repository run "mvn install" from the root of your local copy
  - To create your java EE 6 project run "mvn archetype:generate -DarchetypeGroupId=com.github -DarchetypeArtifactId=java-EE-6-with-java-8 -DarchetypeVersion=1.0 -DgroupId=my-group-id -DartifactId=my-artifact-id" from the directory where you want to create your project
