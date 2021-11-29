---
title: Barcode.DiscountNotAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountNotAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DiscountNotAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.discountnotallowed(v=AX.60)
ms:contentKeyID: 62213676
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.DiscountNotAllowed
dev_langs:
- CSharp
- C++
- VB
---

# DiscountNotAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountNotAllowed As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.DiscountNotAllowed

instance.DiscountNotAllowed = value
```

``` csharp
[DataMemberAttribute]
public bool DiscountNotAllowed { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool DiscountNotAllowed {
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

