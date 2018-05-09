---
title: OperationPermission.OperationName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.OperationName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.operationpermission.operationname(v=AX.60)
ms:contentKeyID: 62211355
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.OperationName
dev_langs:
- CSharp
- C++
- VB
---

# OperationName Property

Gets or sets a value indicating operation name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OPERATIONNAME")> _
<DataMemberAttribute> _
Public Property OperationName As String
    Get
    Set
'Usage
Dim instance As OperationPermission
Dim value As String

value = instance.OperationName

instance.OperationName = value
```

``` csharp
[ColumnAttribute("OPERATIONNAME")]
[DataMemberAttribute]
public string OperationName { get; set; }
```

``` c++
[ColumnAttribute(L"OPERATIONNAME")]
[DataMemberAttribute]
public:
property String^ OperationName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Value indicating operation Name.  

## See Also

#### Reference

[OperationPermission Class](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

