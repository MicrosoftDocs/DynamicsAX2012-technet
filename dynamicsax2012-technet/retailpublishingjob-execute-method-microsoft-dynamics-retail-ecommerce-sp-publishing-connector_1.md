---
title: RetailPublishingJob.Execute Method () (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: Execute Method ()
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.RetailPublishingJob.Execute(Microsoft.SharePoint.Administration.SPJobState)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.retailpublishingjob.execute(v=AX.60)
ms:contentKeyID: 65318521
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Execute Method ()


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides SPPausableJobDefinitionExecute(SPJobState).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub Execute ( _
    jobState As SPJobState _
)
'Usage
Dim instance As RetailPublishingJob
Dim jobState As SPJobState

instance.Execute(jobState)
```

``` csharp
public override void Execute(
    SPJobState jobState
)
```

``` c++
public:
virtual void Execute(
    SPJobState^ jobState
) override
```

#### Parameters

  - jobState  
    Type: SPJobState  

## See Also

#### Reference

[RetailPublishingJob Class](retailpublishingjob-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Execute Overload](retailpublishingjob-execute-method-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

