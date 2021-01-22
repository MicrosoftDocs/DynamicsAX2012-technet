---
title: Cart.TenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.tenderlines(v=AX.60)
ms:contentKeyID: 62206548
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TenderLines
dev_langs:
- CSharp
- C++
- VB
---

# TenderLines Property

Gets or sets the tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLines As IList(Of TenderLine)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As IList(Of TenderLine)

value = instance.TenderLines

instance.TenderLines = value
```

``` csharp
[DataMemberAttribute]
public IList<TenderLine> TenderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<TenderLine^>^ TenderLines {
    IList<TenderLine^>^ get ();
    void set (IList<TenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

