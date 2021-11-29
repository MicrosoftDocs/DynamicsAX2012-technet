---
title: GetOperationPermissionsResponse Constructor (ReadOnlyCollection(OperationPermission)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetOperationPermissionsResponse Constructor (ReadOnlyCollection(OperationPermission))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getoperationpermissionsresponse.getoperationpermissionsresponse(v=AX.60)
ms:contentKeyID: 62212543
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOperationPermissionsResponse Constructor (ReadOnlyCollection(OperationPermission))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetOperationPermissionsResponse](getoperationpermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    operationPermissions As ReadOnlyCollection(Of OperationPermission) _
)
'Usage
Dim operationPermissions As ReadOnlyCollection(Of OperationPermission)

Dim instance As New GetOperationPermissionsResponse(operationPermissions)
```

``` csharp
public GetOperationPermissionsResponse(
    ReadOnlyCollection<OperationPermission> operationPermissions
)
```

``` c++
public:
GetOperationPermissionsResponse(
    ReadOnlyCollection<OperationPermission^>^ operationPermissions
)
```

#### Parameters

  - operationPermissions  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OperationPermission](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetOperationPermissionsResponse Class](getoperationpermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetOperationPermissionsResponse Overload](getoperationpermissionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

