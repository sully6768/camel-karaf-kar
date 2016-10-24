Camel Router Project for Spring-DM (OSGi)
=========================================

To build this project use

    mvn install

You can run this project using he following Maven goal:

    mvn camel:run

To deploy the project in OSGi. For example using Apache ServiceMix
or Apache Karaf, you will copy the generated KAR file under target to:

    <KARAF/FUSE HOME>/deploy

For more help see the Apache Camel documentation

    http://camel.apache.org/
