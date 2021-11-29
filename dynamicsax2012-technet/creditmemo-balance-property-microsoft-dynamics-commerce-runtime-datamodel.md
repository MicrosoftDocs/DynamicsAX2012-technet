---
title: CreditMemo.Balance Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CreditMemo.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.creditmemo.balance(v=AX.60)
ms:contentKeyID: 62208924
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CreditMemo.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the credit memo balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BALANCE")> _
<DataMemberAttribute> _
Public Property Balance As Decimal
    Get
    Set
'Usage
Dim instance As CreditMemo
Dim value As Decimal

value = instance.Balance

instance.Balance = value
```

``` csharp
[ColumnAttribute("BALANCE")]
[DataMemberAttribute]
public decimal Balance { get; set; }
```

``` c++
[ColumnAttribute(L"BALANCE")]
[DataMemberAttribute]
public:
property Decimal Balance {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CreditMemo Class](creditmemo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

