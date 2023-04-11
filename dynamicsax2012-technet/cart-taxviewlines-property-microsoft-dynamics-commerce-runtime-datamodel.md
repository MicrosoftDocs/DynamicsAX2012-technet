---
title: Cart.TaxViewLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxViewLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxViewLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.taxviewlines(v=AX.60)
ms:contentKeyID: 65322080
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TaxViewLines
dev_langs:
- CSharp
- C++
- VB
---

# TaxViewLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxViewLines As IList(Of TaxViewLine)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of TaxViewLine)

value = instance.TaxViewLines

instance.TaxViewLines = value
```

``` csharp
[DataMemberAttribute]
public IList<TaxViewLine> TaxViewLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<TaxViewLine^>^ TaxViewLines {
    IList<TaxViewLine^>^ get ();
    void set (IList<TaxViewLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[TaxViewLine](taxviewline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

