---
title: IDisbursementSlipInfoV1.CardInfo Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables)
TOCTitle: CardInfo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IDisbursementSlipInfoV1.CardInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.transaction.memorytables.idisbursementslipinfov1.cardinfo(v=AX.60)
ms:contentKeyID: 62201988
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables.IDisbursementSlipInfoV1.CardInfo
dev_langs:
- CSharp
- C++
- VB
---

# CardInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Customer identity card information.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardInfo As String
    Get
    Set
'Usage
Dim instance As IDisbursementSlipInfoV1
Dim value As String

value = instance.CardInfo

instance.CardInfo = value
```

``` csharp
string CardInfo { get; set; }
```

``` c++
property String^ CardInfo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IDisbursementSlipInfoV1 Interface](idisbursementslipinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.Transaction.MemoryTables Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-transaction-memorytables-namespace.md)

