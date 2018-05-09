---
title: PriceLine.PriceMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.PriceMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.priceline.pricemethod(v=AX.60)
ms:contentKeyID: 62213691
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.PriceMethod
dev_langs:
- CSharp
- C++
- VB
---

# PriceMethod Property

Gets or sets the price method of this line (e.g. Fixed, Amount off, Percent off).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEMETHOD")> _
<DataMemberAttribute> _
Public Property PriceMethod As PriceMethod
    Get
    Set
'Usage
Dim instance As PriceLine
Dim value As PriceMethod

value = instance.PriceMethod

instance.PriceMethod = value
```

``` csharp
[ColumnAttribute("PRICEMETHOD")]
[DataMemberAttribute]
public PriceMethod PriceMethod { get; set; }
```

``` c++
[ColumnAttribute(L"PRICEMETHOD")]
[DataMemberAttribute]
public:
property PriceMethod PriceMethod {
    PriceMethod get ();
    void set (PriceMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod](pricemethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceMethod](pricemethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PriceLine Class](priceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

