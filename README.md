Maven Archetype For Servlet3 Project
====================================
This project using Servlet 3.

### Install ###
Install Maven archetype using command below :
~~~
mvn install
~~~

### Using ###
After install success, you can see this archetype when create **Maven project** in **Eclipse** or using command below :
~~~
mvn archetype:generate                                          /
    -DarchetypeGroupId=com.anat.structure                       /
    -DarchetypeArtifactId=servlet3-webapp-archetype			    /
    -DarchetypeVersion=1.0                                      /
    -DgroupId=<your_groupId>                                    /
    -DartifactId=<your_artifactId>                              / 
    -DinteractiveMode=false                                     /
~~~