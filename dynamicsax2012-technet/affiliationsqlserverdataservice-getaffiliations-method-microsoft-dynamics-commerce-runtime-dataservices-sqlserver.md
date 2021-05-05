---
title: AffiliationSqlServerDataService.GetAffiliations Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer)
TOCTitle: GetAffiliations Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService.GetAffiliations(Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlserver.affiliationsqlserverdataservice.getaffiliations(v=AX.60)
ms:contentKeyID: 65318900
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.AffiliationSqlServerDataService.GetAffiliations
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliations Method

Gets affiliations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer (in Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer.dll)

## Syntax

``` vb
'Declaration
Public Function GetAffiliations ( _
    request As GetAffiliationsDataRequest _
) As EntityDataServiceResponse(Of Affiliation)
'Usage
Dim instance As AffiliationSqlServerDataService
Dim request As GetAffiliationsDataRequest
Dim returnValue As EntityDataServiceResponse(Of Affiliation)

returnValue = instance.GetAffiliations(request)
```

``` csharp
public EntityDataServiceResponse<Affiliation> GetAffiliations(
    GetAffiliationsDataRequest request
)
```

``` c++
public:
EntityDataServiceResponse<Affiliation^>^ GetAffiliations(
    GetAffiliationsDataRequest^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest](getaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\<[Affiliation](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The data service response with the collection of affiliations.  

## See Also

#### Reference

[AffiliationSqlServerDataService Class](affiliationsqlserverdataservice-class-microsoft-dynamics-commerce-runtime-dataservices-sqlserver.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.SqlServer Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlserver-namespace.md)

