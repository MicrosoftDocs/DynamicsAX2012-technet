---
title: GetOperationPermissionsRequest.OperationId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OperationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsRequest.OperationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getoperationpermissionsrequest.operationid(v=AX.60)
ms:contentKeyID: 62211581
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsRequest.OperationId
dev_langs:
- CSharp
- C++
- VB
---

# OperationId Property

Gets or sets the OperationName to get the permissions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OperationId As RetailOperation
    Get
    Set
'Usage
Dim instance As GetOperationPermissionsRequest
Dim value As RetailOperation

value = instance.OperationId

instance.OperationId = value
```

``` csharp
[DataMemberAttribute]
public RetailOperation OperationId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property RetailOperation OperationId {
    RetailOperation get ();
    void set (RetailOperation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOperationPermissionsRequest Class](getoperationpermissionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

