---
title: ItemMaxRetailPriceIndia.MaximumRetailPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumRetailPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemMaxRetailPriceIndia.MaximumRetailPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemmaxretailpriceindia.maximumretailprice(v=AX.60)
ms:contentKeyID: 62209910
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemMaxRetailPriceIndia.MaximumRetailPrice
dev_langs:
- CSharp
- C++
- VB
---

# MaximumRetailPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item maximum retail price for India.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMRETAILPRICE_IN")> _
<DataMemberAttribute> _
Public Property MaximumRetailPrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As ItemMaxRetailPriceIndia
Dim value As Decimal

value = instance.MaximumRetailPrice
```

``` csharp
[ColumnAttribute("MAXIMUMRETAILPRICE_IN")]
[DataMemberAttribute]
public decimal MaximumRetailPrice { get; internal set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMRETAILPRICE_IN")]
[DataMemberAttribute]
public:
property Decimal MaximumRetailPrice {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ItemMaxRetailPriceIndia Class](itemmaxretailpriceindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

