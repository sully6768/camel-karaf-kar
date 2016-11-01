Camel Karaf Kar Deployment Example (OSGi)
=========================================

To build this project use

    mvn install

You can run this project using he following Maven goal:

    mvn camel:run

## Deploy

To deploy the KAR file project into the Karaf instance you will first need to 
install the KAR feature:

    features:install kar

Once the KAR feature is installed copy the generated KAR file under 
the projects target directory to:

    <KARAF/FUSE HOME>/deploy

For more help see the Apache Camel documentation

    http://camel.apache.org/
