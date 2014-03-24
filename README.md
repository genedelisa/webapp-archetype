#Webapp-archetype

This is a maven archetype for creating a Java webapp.

It seems that most existing webapp archetypes miss important file/directories.

## Usage

Install it to your local repo:

mvn install

Then generate a new project

mvn archetype:generate  -DarchetypeGroupId=com.rockhoppertech -DarchetypeArtifactId=webapp-archetype -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=com.yourdomain -DartifactId=mywebapp

