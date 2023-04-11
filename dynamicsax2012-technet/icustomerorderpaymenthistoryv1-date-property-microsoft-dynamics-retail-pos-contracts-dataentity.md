---
title: ICustomerOrderPaymentHistoryV1.Date Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Date Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderPaymentHistoryV1.Date
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerorderpaymenthistoryv1.date(v=AX.60)
ms:contentKeyID: 49833465
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderPaymentHistoryV1.Date
dev_langs:
- CSharp
- C++
- VB
---

# Date Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Payment date

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Date As DateTime
    Get
    Set
'Usage
Dim instance As ICustomerOrderPaymentHistoryV1
Dim value As DateTime

value = instance.Date

instance.Date = value
```

``` csharp
DateTime Date { get; set; }
```

``` c++
property DateTime Date {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerOrderPaymentHistoryV1 Interface](icustomerorderpaymenthistoryv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

