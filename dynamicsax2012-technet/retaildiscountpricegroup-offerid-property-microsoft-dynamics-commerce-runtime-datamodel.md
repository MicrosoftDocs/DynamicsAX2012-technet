---
title: RetailDiscountPriceGroup.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountPriceGroup.OfferId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountpricegroup.offerid(v=AX.60)
ms:contentKeyID: 62207253
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountPriceGroup.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the price group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OFFERID")> _
<DataMemberAttribute> _
Public Property OfferId As String
    Get
    Set
'Usage
Dim instance As RetailDiscountPriceGroup
Dim value As String

value = instance.OfferId

instance.OfferId = value
```

``` csharp
[ColumnAttribute("OFFERID")]
[DataMemberAttribute]
public string OfferId { get; set; }
```

``` c++
[ColumnAttribute(L"OFFERID")]
[DataMemberAttribute]
public:
property String^ OfferId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountPriceGroup Class](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

