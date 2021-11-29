---
title: RetailPublishingJob Constructor (String, , String) (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: RetailPublishingJob Constructor (String, , String)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.RetailPublishingJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPService,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.retailpublishingjob.retailpublishingjob(v=AX.60)
ms:contentKeyID: 65315796
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RetailPublishingJob Constructor (String, , String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    jobName As String, _
    service As SPService, _
    jobSettingsName As String _
)
'Usage
Dim jobName As String
Dim service As SPService
Dim jobSettingsName As String

Dim instance As New RetailPublishingJob(jobName, _
    service, jobSettingsName)
```

``` csharp
public RetailPublishingJob(
    string jobName,
    SPService service,
    string jobSettingsName
)
```

``` c++
public:
RetailPublishingJob(
    String^ jobName, 
    SPService^ service, 
    String^ jobSettingsName
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - service  
    Type: SPService  

<!-- end list -->

  - jobSettingsName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[RetailPublishingJob Class](retailpublishingjob-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[RetailPublishingJob Overload](retailpublishingjob-constructor-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

