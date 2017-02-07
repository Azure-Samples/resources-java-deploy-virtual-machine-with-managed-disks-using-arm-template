---
services: Resources
platforms: java
author: anuchandy
---

#Getting Started with Resources - Deploy Virtual Machine Using ARM Template - in Java #


      Main function which runs the actual sample.
      @param azure instance of the azure client
      @return true if sample runs successfully
     

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/resources-java-deploy-virtual-machine-with-managed-disks-using-arm-template.git

    cd resources-java-deploy-virtual-machine-with-managed-disks-using-arm-template

    mvn clean compile exec:java

## More information ##

[http://azure.com/java] (http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.