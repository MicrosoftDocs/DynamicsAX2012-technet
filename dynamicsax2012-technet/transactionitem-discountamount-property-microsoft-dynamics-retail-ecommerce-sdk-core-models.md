﻿---
title: TransactionItem.DiscountAmount Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: DiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.DiscountAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transactionitem.discountamount(v=AX.60)
ms:contentKeyID: 65317380
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.DiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# DiscountAmount Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Decimal

value = instance.DiscountAmount

instance.DiscountAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal DiscountAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal DiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)
