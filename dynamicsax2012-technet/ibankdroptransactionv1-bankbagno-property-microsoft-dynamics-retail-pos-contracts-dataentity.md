---
title: IBankDropTransactionV1.BankBagNo Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BankBagNo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBankDropTransactionV1.BankBagNo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibankdroptransactionv1.bankbagno(v=AX.60)
ms:contentKeyID: 49839925
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBankDropTransactionV1.BankBagNo
dev_langs:
- CSharp
- C++
- VB
---

# BankBagNo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BankBagNo As String
    Get
    Set
'Usage
Dim instance As IBankDropTransactionV1
Dim value As String

value = instance.BankBagNo

instance.BankBagNo = value
```

``` csharp
string BankBagNo { get; set; }
```

``` c++
property String^ BankBagNo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IBankDropTransactionV1 Interface](ibankdroptransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

