---
title: DiscountLine.OfferName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.OfferName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.offername(v=AX.60)
ms:contentKeyID: 62205956
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.OfferName
dev_langs:
- CSharp
- C++
- VB
---

# OfferName Property

Gets or sets the offer name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFERNAME")> _
Public Property OfferName As String
    Get
    Set
'Usage
Dim instance As DiscountLine
Dim value As String

value = instance.OfferName

instance.OfferName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFERNAME")]
public string OfferName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFERNAME")]
public:
property String^ OfferName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

