# java-EE-6-with-java-8-archetype

Maven archtype used to create a new Java EE 6 project with java 8.
Archetype groupId and artifactId can be found in the main pom.

Steps:

  - clone the archtype to your folder
  - run "mvn install" from the root of the project
  - run "mvn archetype:generate -DarchetypeGroupId=<archetype-groupId> -DarchetypeArtifactId=<archetype-artifactId> -DarchetypeVersion=<archetype-version> -DgroupId=<my.groupid> -DartifactId=<my-artifactId>"
  to create the project from the archetype
