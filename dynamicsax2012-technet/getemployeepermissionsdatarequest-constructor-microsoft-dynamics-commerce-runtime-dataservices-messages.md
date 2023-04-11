---
title: GetEmployeePermissionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetEmployeePermissionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeePermissionsDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeepermissionsdatarequest.getemployeepermissionsdatarequest(v=AX.60)
ms:contentKeyID: 65321256
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeePermissionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeePermissionsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetEmployeePermissionsDataRequest](getemployeepermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    staffId As String, _
    columnSet As ColumnSet _
)
'Usage
Dim staffId As String
Dim columnSet As ColumnSet

Dim instance As New GetEmployeePermissionsDataRequest(staffId, _
    columnSet)
```

``` csharp
public GetEmployeePermissionsDataRequest(
    string staffId,
    ColumnSet columnSet
)
```

``` c++
public:
GetEmployeePermissionsDataRequest(
    String^ staffId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetEmployeePermissionsDataRequest Class](getemployeepermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

