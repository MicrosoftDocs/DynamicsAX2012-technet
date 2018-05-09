---
title: PublishingConnectorServiceInstance.UnprovisionLink Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: UnprovisionLink Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.UnprovisionLink
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingconnectorserviceinstance.unprovisionlink(v=AX.60)
ms:contentKeyID: 65318413
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingConnectorServiceInstance.UnprovisionLink
dev_langs:
- CSharp
- C++
- VB
---

# UnprovisionLink Property

This member overrides SPServiceInstanceUnprovisionLink().

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property UnprovisionLink As SPActionLink
    Get
'Usage
Dim instance As PublishingConnectorServiceInstance
Dim value As SPActionLink

value = instance.UnprovisionLink
```

``` csharp
public override SPActionLink UnprovisionLink { get; }
```

``` c++
public:
virtual property SPActionLink^ UnprovisionLink {
    SPActionLink^ get () override;
}
```

#### Property Value

Type: SPActionLink  

## See Also

#### Reference

[PublishingConnectorServiceInstance Class](publishingconnectorserviceinstance-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

