---
page_type: sample
languages:
- java
products:
- azure
description: "List all virtual machine image publishers and list all virtual machine images published by Canonical, Red Hat and SUSE."
urlFragment: compute-java-list-vm-images
---

# List Azure Virtual Machine Images (Java)


List all virtual machine image publishers and list all virtual machine images published by Canonical, Red Hat and SUSE by browsing through locations, publishers, offers, SKUs and images.

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/compute-java-list-vm-images.git
cd compute-java-list-vm-images
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
