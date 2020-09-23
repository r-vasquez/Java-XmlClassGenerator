## Xml Class Generator using Apache CFX XJC Maven Plugin

Since Java 9 xjc doesn't come in the JDK, so in order to use JAXB and create binding Java classes 
based on an existing XSD it is necessary to use a 
plugin such as the [Apache CXF XJC Maven Plugin](http://cxf.apache.org/cxf-xjc-plugin.html)

To generate just clone the repo and use:

`mvn clean install`

All the generated classes will be in target package that is put in the tag \<packagename> inside the pom.xml 