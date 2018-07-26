Java EE 7 with Spring 4 recommended by WildFly
===============================

This BOM builds on the Java EE full profile BOM, adding Spring 4.
  
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.wildfly.bom</groupId>
               <artifactId>wildfly-javaee7-with-spring4</artifactId>
               <version>14.0.0.Alpha1</version>
               <type>pom</type>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
