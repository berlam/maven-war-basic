maven-war-basic
===============

Understanding maven reactor order can get confusing. This is to help beginners to start with the maven war plugin.
You do not have to execute `mvn clean install` everytime. Just build it with `mvn -pl -am :child1 package`.
