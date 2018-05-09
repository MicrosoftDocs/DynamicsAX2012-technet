---
title: Shift.IsShared Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsShared Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.IsShared
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.isshared(v=AX.60)
ms:contentKeyID: 65316403
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.IsShared
dev_langs:
- CSharp
- C++
- VB
---

# IsShared Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISSHARED")> _
<DataMemberAttribute> _
Public Property IsShared As Boolean
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Boolean

value = instance.IsShared

instance.IsShared = value
```

``` csharp
[ColumnAttribute("ISSHARED")]
[DataMemberAttribute]
public bool IsShared { get; set; }
```

``` c++
[ColumnAttribute(L"ISSHARED")]
[DataMemberAttribute]
public:
property bool IsShared {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

