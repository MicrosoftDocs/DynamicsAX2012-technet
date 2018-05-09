---
title: ProductChangeTrackingInformation.ChangeAction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeAction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.ChangeAction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.changeaction(v=AX.60)
ms:contentKeyID: 62208091
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.ChangeAction
dev_langs:
- CSharp
- C++
- VB
---

# ChangeAction Property

Gets a value indicating the nature of change in the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ChangeAction As ChangeAction
    Get
    Private Set
'Usage
Dim instance As ProductChangeTrackingInformation
Dim value As ChangeAction

value = instance.ChangeAction
```

``` csharp
[IgnoreDataMemberAttribute]
public ChangeAction ChangeAction { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ChangeAction ChangeAction {
    ChangeAction get ();
    private: void set (ChangeAction value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction](changeaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChangeAction](changeaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

