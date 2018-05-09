---
title: Cart.QuotationExpiryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuotationExpiryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.QuotationExpiryDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cart.quotationexpirydate(v=AX.60)
ms:contentKeyID: 62214361
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.QuotationExpiryDate
dev_langs:
- CSharp
- C++
- VB
---

# QuotationExpiryDate Property

Gets or sets the expiration date for a quote.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXPIRYDATE")> _
Public Property QuotationExpiryDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of DateTimeOffset)

value = instance.QuotationExpiryDate

instance.QuotationExpiryDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXPIRYDATE")]
public Nullable<DateTimeOffset> QuotationExpiryDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXPIRYDATE")]
public:
property Nullable<DateTimeOffset> QuotationExpiryDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

