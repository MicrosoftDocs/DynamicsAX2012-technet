---
title: PublishingProcessorWrapper.InitializeLifetimeService Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: InitializeLifetimeService Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingProcessorWrapper.InitializeLifetimeService
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.publishingprocessorwrapper.initializelifetimeservice(v=AX.60)
ms:contentKeyID: 65316934
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.PublishingProcessorWrapper.InitializeLifetimeService
dev_langs:
- CSharp
- C++
- VB
---

# InitializeLifetimeService Method

This member overrides [MarshalByRefObject.InitializeLifetimeService()](https://technet.microsoft.com/en-us/library/zwt5tzck\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function InitializeLifetimeService As Object
'Usage
Dim instance As PublishingProcessorWrapper
Dim returnValue As Object

returnValue = instance.InitializeLifetimeService()
```

``` csharp
public override Object InitializeLifetimeService()
```

``` c++
public:
virtual Object^ InitializeLifetimeService() override
```

#### Return Value

Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[PublishingProcessorWrapper Class](publishingprocessorwrapper-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

