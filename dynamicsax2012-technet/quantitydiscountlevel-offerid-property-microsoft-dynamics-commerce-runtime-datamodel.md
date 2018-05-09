---
title: QuantityDiscountLevel.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.OfferId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.quantitydiscountlevel.offerid(v=AX.60)
ms:contentKeyID: 49821244
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property

Gets the quantity discount offer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MULTIBUYID")> _
<DataMemberAttribute> _
Public Property OfferId As String
    Get
    Set
'Usage
Dim instance As QuantityDiscountLevel
Dim value As String

value = instance.OfferId

instance.OfferId = value
```

``` csharp
[ColumnAttribute("MULTIBUYID")]
[DataMemberAttribute]
public string OfferId { get; set; }
```

``` c++
[ColumnAttribute(L"MULTIBUYID")]
[DataMemberAttribute]
public:
property String^ OfferId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[QuantityDiscountLevel Class](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

