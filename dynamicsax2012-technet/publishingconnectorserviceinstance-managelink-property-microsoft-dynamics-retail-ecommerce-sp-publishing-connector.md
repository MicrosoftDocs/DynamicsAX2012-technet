---
title: PublishingConnectorServiceInstance.ManageLink Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: ManageLink Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.ManageLink
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingconnectorserviceinstance.managelink(v=AX.60)
ms:contentKeyID: 65315702
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.ManageLink
dev_langs:
- CSharp
- C++
- VB
---

# ManageLink Property

This member overrides SPServiceInstanceManageLink().

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ManageLink As SPActionLink
    Get
'Usage
Dim instance As PublishingConnectorServiceInstance
Dim value As SPActionLink

value = instance.ManageLink
```

``` csharp
public override SPActionLink ManageLink { get; }
```

``` c++
public:
virtual property SPActionLink^ ManageLink {
    SPActionLink^ get () override;
}
```

#### Property Value

Type: SPActionLink  

## See Also

#### Reference

[PublishingConnectorServiceInstance Class](publishingconnectorserviceinstance-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

