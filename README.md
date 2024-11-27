# WSO2_APIM_Customizations

### 1. wso2mi-authorization-handler-1.0.0
This maven project contains the source code which can be used to apply role based access control to APIs in the wso2 micro integrator without using wso2 api manager. 
Clone this repository, make changes to AuthorizationHandler.java file if required, change the directory to wso2mi-authorization-handler-1.0.0 and build the project using "mvn clean install" to generate the jar file which can be found in /target directory. 
Copy and paste it to <MI_HOME>/lib and refer to it from the API.
