---
title: CartLine.OriginalPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OriginalPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.OriginalPrice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.originalprice(v=AX.60)
ms:contentKeyID: 62208915
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.OriginalPrice
dev_langs:
- CSharp
- C++
- VB
---

# OriginalPrice Property

Gets or sets the original price of the product before any price overrides.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OriginalPrice As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Nullable(Of Decimal)

value = instance.OriginalPrice

instance.OriginalPrice = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> OriginalPrice { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> OriginalPrice {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## Remarks

If the price has not been overridden, then the value will remain null.

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

