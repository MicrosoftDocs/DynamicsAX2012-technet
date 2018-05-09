---
title: ICustomerV1.CreditLimit Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CreditLimit Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CreditLimit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.creditlimit(v=AX.60)
ms:contentKeyID: 47129196
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CreditLimit
dev_langs:
- CSharp
- C++
- VB
---

# CreditLimit Property

Gets or sets the credit limit amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CreditLimit As Decimal
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As Decimal

value = instance.CreditLimit

instance.CreditLimit = value
```

``` csharp
decimal CreditLimit { get; set; }
```

``` c++
property Decimal CreditLimit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

