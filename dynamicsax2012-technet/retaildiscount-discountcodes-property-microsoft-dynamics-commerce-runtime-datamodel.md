---
title: RetailDiscount.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.discountcodes(v=AX.60)
ms:contentKeyID: 62213212
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property

Gets or sets the retail discount codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodes As IList(Of DiscountCode)
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As IList(Of DiscountCode)

value = instance.DiscountCodes

instance.DiscountCodes = value
```

``` csharp
[DataMemberAttribute]
public IList<DiscountCode> DiscountCodes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<DiscountCode^>^ DiscountCodes {
    IList<DiscountCode^>^ get ();
    void set (IList<DiscountCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

