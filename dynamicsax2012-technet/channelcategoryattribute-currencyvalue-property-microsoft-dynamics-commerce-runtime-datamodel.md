---
title: ChannelCategoryAttribute.CurrencyValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CurrencyValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.currencyvalue(v=AX.60)
ms:contentKeyID: 65319344
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CurrencyValue
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyValue Property

Gets the currency value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCYVALUE")> _
Public ReadOnly Property CurrencyValue As Decimal
    Get
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As Decimal

value = instance.CurrencyValue
```

``` csharp
[ColumnAttribute("CURRENCYVALUE")]
public decimal CurrencyValue { get; }
```

``` c++
[ColumnAttribute(L"CURRENCYVALUE")]
public:
property Decimal CurrencyValue {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

