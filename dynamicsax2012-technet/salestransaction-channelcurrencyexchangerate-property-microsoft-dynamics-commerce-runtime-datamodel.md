---
title: SalesTransaction.ChannelCurrencyExchangeRate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelCurrencyExchangeRate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChannelCurrencyExchangeRate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.channelcurrencyexchangerate(v=AX.60)
ms:contentKeyID: 65315729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChannelCurrencyExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCurrencyExchangeRate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("EXCHRATE")> _
Public Property ChannelCurrencyExchangeRate As Decimal
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Decimal

value = instance.ChannelCurrencyExchangeRate

instance.ChannelCurrencyExchangeRate = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("EXCHRATE")]
public decimal ChannelCurrencyExchangeRate { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"EXCHRATE")]
public:
property Decimal ChannelCurrencyExchangeRate {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

