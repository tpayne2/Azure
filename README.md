# Azure
Azure Samples for simple Java App

mvn archetype:generate "-DgroupId=example.demo" "-DartifactId=helloworld" "-DarchetypeArtifactId=maven-archetype-webapp" -Dversion=1.0-SNAPSHOT
cd helloworld
mvn com.microsoft.azure:azure-webapp-maven-plugin:1.9.1:config
mvn package azure-webapp:deploy
