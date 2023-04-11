---
title: ISCJournalTransactionV1.Counted Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Counted Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.Counted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscjournaltransactionv1.counted(v=AX.60)
ms:contentKeyID: 47344469
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISCJournalTransactionV1.Counted
dev_langs:
- CSharp
- C++
- VB
---

# Counted Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Counted As Decimal
    Get
    Set
'Usage
Dim instance As ISCJournalTransactionV1
Dim value As Decimal

value = instance.Counted

instance.Counted = value
```

``` csharp
decimal Counted { get; set; }
```

``` c++
property Decimal Counted {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) decimal value.  

## See Also

#### Reference

[ISCJournalTransactionV1 Interface](iscjournaltransactionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

