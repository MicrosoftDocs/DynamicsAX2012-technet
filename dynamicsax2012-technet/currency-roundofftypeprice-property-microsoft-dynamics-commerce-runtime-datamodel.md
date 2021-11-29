---
title: Currency.RoundOffTypePrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundOffTypePrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffTypePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currency.roundofftypeprice(v=AX.60)
ms:contentKeyID: 62212351
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffTypePrice
dev_langs:
- CSharp
- C++
- VB
---

# RoundOffTypePrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the round off type price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ROUNDOFFTYPEPRICE")> _
<DataMemberAttribute> _
Public Property RoundOffTypePrice As Integer
    Get
    Set
'Usage
Dim instance As Currency
Dim value As Integer

value = instance.RoundOffTypePrice

instance.RoundOffTypePrice = value
```

``` csharp
[ColumnAttribute("ROUNDOFFTYPEPRICE")]
[DataMemberAttribute]
public int RoundOffTypePrice { get; set; }
```

``` c++
[ColumnAttribute(L"ROUNDOFFTYPEPRICE")]
[DataMemberAttribute]
public:
property int RoundOffTypePrice {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Currency Class](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

