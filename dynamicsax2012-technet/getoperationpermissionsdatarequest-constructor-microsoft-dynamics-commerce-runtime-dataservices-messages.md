---
title: GetOperationPermissionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetOperationPermissionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getoperationpermissionsdatarequest.getoperationpermissionsdatarequest(v=AX.60)
ms:contentKeyID: 65321752
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetOperationPermissionsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetOperationPermissionsDataRequest](getoperationpermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    operationId As RetailOperation, _
    columns As ColumnSet _
)
'Usage
Dim operationId As RetailOperation
Dim columns As ColumnSet

Dim instance As New GetOperationPermissionsDataRequest(operationId, _
    columns)
```

``` csharp
public GetOperationPermissionsDataRequest(
    RetailOperation operationId,
    ColumnSet columns
)
```

``` c++
public:
GetOperationPermissionsDataRequest(
    RetailOperation operationId, 
    ColumnSet^ columns
)
```

#### Parameters

  - operationId  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetOperationPermissionsDataRequest Class](getoperationpermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

