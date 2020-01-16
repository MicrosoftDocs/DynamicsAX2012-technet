---
title: OperationPermission.OperationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.OperationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.operationpermission.operationid(v=AX.60)
ms:contentKeyID: 62211748
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.OperationId
dev_langs:
- CSharp
- C++
- VB
---

# OperationId Property

Gets or sets a value indicating operation Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OPERATIONID")> _
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property OperationId As Integer
    Get
    Set
'Usage
Dim instance As OperationPermission
Dim value As Integer

value = instance.OperationId

instance.OperationId = value
```

``` csharp
[ColumnAttribute("OPERATIONID")]
[RequiredAttribute]
[DataMemberAttribute]
public int OperationId { get; set; }
```

``` c++
[ColumnAttribute(L"OPERATIONID")]
[RequiredAttribute]
[DataMemberAttribute]
public:
property int OperationId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Value indicating operation Id.  

## See Also

#### Reference

[OperationPermission Class](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

