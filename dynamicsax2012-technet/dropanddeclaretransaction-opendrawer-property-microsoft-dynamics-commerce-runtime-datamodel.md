---
title: DropAndDeclareTransaction.OpenDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.OpenDrawer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.dropanddeclaretransaction.opendrawer(v=AX.60)
ms:contentKeyID: 62210692
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawer Property

Gets or sets a value indicating whether the open drawer is true/ false.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPENDRAWER")> _
Public Property OpenDrawer As Boolean
    Get
    Set
'Usage
Dim instance As DropAndDeclareTransaction
Dim value As Boolean

value = instance.OpenDrawer

instance.OpenDrawer = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPENDRAWER")]
public bool OpenDrawer { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPENDRAWER")]
public:
property bool OpenDrawer {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DropAndDeclareTransaction Class](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

