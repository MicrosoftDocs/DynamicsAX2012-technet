---
title: Barcode.NegativeQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NegativeQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.NegativeQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.negativequantity(v=AX.60)
ms:contentKeyID: 62211036
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.NegativeQuantity
dev_langs:
- CSharp
- C++
- VB
---

# NegativeQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NegativeQuantity As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.NegativeQuantity

instance.NegativeQuantity = value
```

``` csharp
[DataMemberAttribute]
public bool NegativeQuantity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool NegativeQuantity {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

