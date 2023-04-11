---
title: SalesLine.DiscountLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DiscountLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.discountlines(v=AX.60)
ms:contentKeyID: 49831429
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.DiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection of all discounts belonging to the salesline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountLines As Collection(Of DiscountLine)
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Collection(Of DiscountLine)

value = instance.DiscountLines

instance.DiscountLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<DiscountLine> DiscountLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<DiscountLine^>^ DiscountLines {
    Collection<DiscountLine^>^ get ();
    void set (Collection<DiscountLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

