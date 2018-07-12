---
title: Troubleshooting System Services
TOCTitle: Troubleshooting System Services
ms:assetid: 8017c786-0b8d-420f-850d-2adbe2dbc79d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg862502(v=AX.60)
ms:contentKeyID: 35246133
ms.date: 04/02/2014
mtps_version: v=AX.60
dev_langs:
- xml
---

# Troubleshooting System Services 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes troubleshooting if you encounter issues when calling the system services in Microsoft Dynamics AX.

## Maximum Number of Items Error

When calling the metadata service, you may receive the following error:

Maximum number of items that can be serialized or deserialized in an object graph is '65535'.

The Windows Communication Foundation (WCF) data contract serializer has a default number of objects that can be serialized. To resolve this issue, add a behavior to the client endpoint and set the dataContractSerializer.maxItemsInObject property to a larger value. For more information, see [DataContractSerializer.MaxItemsInObjectGraph Property](http://go.microsoft.com/fwlink/?linkid=149822).

This behavior is in the client app.config file. The following code shows an example of the behavior which is located in the System.ServiceModel node.

``` xml
      <behaviors>
        <endpointBehaviors>
          <behavior name="MetadataEndpointBehavior">
            <dataContractSerializer maxItemsInObjectGraph="524288" />
          </behavior>
        </endpointBehaviors>
      </behaviors>
```

## Setting maxItemsInObjectGraph By Using the AX 2012 Configuration Utility

You may encounter the maximum number of items error when using Microsoft SQL Server Reporting Services. Use the following procedure to set the value for maxItemsInObjectGraph on the computer where you have configured Reporting Services.

### To Set maxItemsInObjectGraph

1.  Open the AX 2012 Configuration utility. For more information, see [About the Microsoft Dynamics AX 2012 Configuration utility](about-the-microsoft-dynamics-ax-2012-configuration-utility.md).

2.  On the **Connection** tab, click **Configure Services**.

3.  In the Service Configuration Editor, open the **Advanced** node, click **Endpoint Behaviors**, and then create a new behavior.

4.  Enter **MetadataEndpointBehavior** in the **Name** field.

5.  Right-click **MetadataEndpointBehavior** and then click **Add Endpoint Behavior Element Extension**.

6.  Right-click **dataContractSerializer** in the **Configuration** pane and set the value for **MaxItemsInObjectGraph** to the desired value, for example, 524288.

7.  Open the **Client**\\**Endpoints** node and right-click **MetadataServiceEndpoint**.

8.  Set the value for **BehaviorConfiguration** to **MetadataEndpointBehavior**.

## Message Size Error in Metadata Service

A call to the metadata service may result in an exception because the message size of the returned data exceeds the maximum size defined in the app.config. Therefore, you should increase the maxBufferSize and maxReceivedMessages settings in the app.config (2147483647 is the maximum). This setting should be updated in the app.config on both the server and the client. These settings are found in the \<System.ServiceModel\>\<Bindings\>\<%bindingType%\>\<binding\> element.

  


