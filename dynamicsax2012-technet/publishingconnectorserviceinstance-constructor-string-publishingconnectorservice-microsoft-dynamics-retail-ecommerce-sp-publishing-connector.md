---
title: PublishingConnectorServiceInstance Constructor (String, , PublishingConnectorService) (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: PublishingConnectorServiceInstance Constructor (String, , PublishingConnectorService)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.#ctor(System.String,Microsoft.SharePoint.Administration.SPServer,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorService)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingconnectorserviceinstance.publishingconnectorserviceinstance(v=AX.60)
ms:contentKeyID: 65316875
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PublishingConnectorServiceInstance Constructor (String, , PublishingConnectorService)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    instanceName As String, _
    server As SPServer, _
    service As PublishingConnectorService _
)
'Usage
Dim instanceName As String
Dim server As SPServer
Dim service As PublishingConnectorService

Dim instance As New PublishingConnectorServiceInstance(instanceName, _
    server, service)
```

``` csharp
public PublishingConnectorServiceInstance(
    string instanceName,
    SPServer server,
    PublishingConnectorService service
)
```

``` c++
public:
PublishingConnectorServiceInstance(
    String^ instanceName, 
    SPServer^ server, 
    PublishingConnectorService^ service
)
```

#### Parameters

  - instanceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - server  
    Type: SPServer  

<!-- end list -->

  - service  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorService](publishingconnectorservice-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)  

## See Also

#### Reference

[PublishingConnectorServiceInstance Class](publishingconnectorserviceinstance-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[PublishingConnectorServiceInstance Overload](publishingconnectorserviceinstance-constructor-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

