---
title: Barcode.HasLinkedItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HasLinkedItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.HasLinkedItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.haslinkeditem(v=AX.60)
ms:contentKeyID: 65319788
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.HasLinkedItem
dev_langs:
- CSharp
- C++
- VB
---

# HasLinkedItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property HasLinkedItem As Boolean
    Get
    Private Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.HasLinkedItem
```

``` csharp
[IgnoreDataMemberAttribute]
public bool HasLinkedItem { get; private set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool HasLinkedItem {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

