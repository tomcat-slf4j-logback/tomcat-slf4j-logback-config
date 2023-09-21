Notable Changes
---------------
Release 1.4.0

 - Update logback/slf4j licenses
 - Add license and notice for jackson
 - Add snippet for logstash in logback-access and logback xml files
 - Add tomcat notice
 - note: Tried to see about shading logback access but it has no access to the tomcat classloader needed so that cannot be shaded.  So access logs for logback and logstash will still require how those are documented on setup.

Release 1.3.0

 - Require java 8

Release 1.2.0

 - Build updates / using parent with changes to dependency stack to optional

Release 1.1.0

 - Split up project into individual pieces.  The Config manages defaults across the project for team. See Individual tomcat modules for more details [tomcat-slf4j-logback](https://github.com/tomcat-slf4j-logback).
