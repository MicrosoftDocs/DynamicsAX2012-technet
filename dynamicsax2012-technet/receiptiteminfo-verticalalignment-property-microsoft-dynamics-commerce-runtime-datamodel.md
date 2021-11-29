---
title: ReceiptItemInfo.VerticalAlignment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VerticalAlignment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.VerticalAlignment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptiteminfo.verticalalignment(v=AX.60)
ms:contentKeyID: 62214637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptItemInfo.VerticalAlignment
dev_langs:
- CSharp
- C++
- VB
---

# VerticalAlignment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets property for VertAlign.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property VerticalAlignment As Alignment
    Get
    Set
'Usage
Dim instance As ReceiptItemInfo
Dim value As Alignment

value = instance.VerticalAlignment

instance.VerticalAlignment = value
```

``` csharp
public Alignment VerticalAlignment { get; set; }
```

``` c++
public:
property Alignment VerticalAlignment {
    Alignment get ();
    void set (Alignment value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Alignment](alignment-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Alignment](alignment-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ReceiptItemInfo Class](receiptiteminfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

