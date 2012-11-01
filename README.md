

Install Ice in local Maven repository
=======================================

         $ mvn -e install:install-file \
           -Dfile=/opt/ice/lib/ant-ice.jar -DpomFile=contrib/ant-ice-3.4.2.pom 
           
         $ mvn -e install:install-file \
           -Dfile=/opt/ice/lib/Ice.jar -DpomFile=contrib/ice-3.4.2.pom 


Running the Server
==================

         $ mvn exec:java -Dexec.mainClass=com.samsung.paas.Server
         

Running the Client
==================

         $ mvn exec:java -Dexec.mainClass=com.samsung.paas.Client         
