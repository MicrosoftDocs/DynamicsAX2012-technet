---
title: PublishingConnectorServiceInstance.ProvisionLink Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: ProvisionLink Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.ProvisionLink
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingconnectorserviceinstance.provisionlink(v=AX.60)
ms:contentKeyID: 65317760
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.ProvisionLink
dev_langs:
- CSharp
- C++
- VB
---

# ProvisionLink Property

This member overrides SPServiceInstanceProvisionLink().

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property ProvisionLink As SPActionLink
    Get
'Usage
Dim instance As PublishingConnectorServiceInstance
Dim value As SPActionLink

value = instance.ProvisionLink
```

``` csharp
public override SPActionLink ProvisionLink { get; }
```

``` c++
public:
virtual property SPActionLink^ ProvisionLink {
    SPActionLink^ get () override;
}
```

#### Property Value

Type: SPActionLink  

## See Also

#### Reference

[PublishingConnectorServiceInstance Class](publishingconnectorserviceinstance-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

