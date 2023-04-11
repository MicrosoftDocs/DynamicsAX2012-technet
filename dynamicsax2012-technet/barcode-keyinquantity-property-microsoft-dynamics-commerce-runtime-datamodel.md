---
title: Barcode.KeyInQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyInQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.KeyInQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.keyinquantity(v=AX.60)
ms:contentKeyID: 62211771
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.KeyInQuantity
dev_langs:
- CSharp
- C++
- VB
---

# KeyInQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property KeyInQuantity As KeyInQuantities
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As KeyInQuantities

value = instance.KeyInQuantity

instance.KeyInQuantity = value
```

``` csharp
[IgnoreDataMemberAttribute]
public KeyInQuantities KeyInQuantity { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property KeyInQuantities KeyInQuantity {
    KeyInQuantities get ();
    void set (KeyInQuantities value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KeyInQuantities](keyinquantities-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

