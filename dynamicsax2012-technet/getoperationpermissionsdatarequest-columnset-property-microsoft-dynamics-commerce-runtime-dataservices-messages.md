---
title: GetOperationPermissionsDataRequest.ColumnSet Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ColumnSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.ColumnSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getoperationpermissionsdatarequest.columnset(v=AX.60)
ms:contentKeyID: 65318180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOperationPermissionsDataRequest.ColumnSet
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet Property

Gets the column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ColumnSet As ColumnSet
    Get
    Private Set
'Usage
Dim instance As GetOperationPermissionsDataRequest
Dim value As ColumnSet

value = instance.ColumnSet
```

``` csharp
[DataMemberAttribute]
public ColumnSet ColumnSet { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ColumnSet^ ColumnSet {
    ColumnSet^ get ();
    private: void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
The column set.  

## See Also

#### Reference

[GetOperationPermissionsDataRequest Class](getoperationpermissionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

