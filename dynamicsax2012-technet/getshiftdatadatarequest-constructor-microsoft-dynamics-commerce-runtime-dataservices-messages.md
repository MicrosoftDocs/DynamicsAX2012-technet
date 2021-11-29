---
title: GetShiftDataDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetShiftDataDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshiftdatadatarequest.getshiftdatadatarequest(v=AX.60)
ms:contentKeyID: 65317329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftDataDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftDataDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShiftDataDataRequest](getshiftdatadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As ShiftDataQueryCriteria, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim criteria As ShiftDataQueryCriteria
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetShiftDataDataRequest(criteria, _
    queryResultSettings)
```

``` csharp
public GetShiftDataDataRequest(
    ShiftDataQueryCriteria criteria,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetShiftDataDataRequest(
    ShiftDataQueryCriteria^ criteria, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetShiftDataDataRequest Class](getshiftdatadatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

