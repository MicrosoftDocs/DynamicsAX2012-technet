---
title: ICustomerV1.CreditRating Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CreditRating Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CreditRating
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.creditrating(v=AX.60)
ms:contentKeyID: 47128280
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CreditRating
dev_langs:
- CSharp
- C++
- VB
---

# CreditRating Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the credit rating.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CreditRating As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.CreditRating

instance.CreditRating = value
```

``` csharp
string CreditRating { get; set; }
```

``` c++
property String^ CreditRating {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

