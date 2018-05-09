---
title: RetailDiscount.DiscountLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.discountlines(v=AX.60)
ms:contentKeyID: 62213731
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLines Property

Gets or sets the retail discount lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountLines As IList(Of RetailDiscountLine)
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As IList(Of RetailDiscountLine)

value = instance.DiscountLines

instance.DiscountLines = value
```

``` csharp
[DataMemberAttribute]
public IList<RetailDiscountLine> DiscountLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<RetailDiscountLine^>^ DiscountLines {
    IList<RetailDiscountLine^>^ get ();
    void set (IList<RetailDiscountLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

