---
title: ITriggersV1.CashManagementTriggers Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: CashManagementTriggers Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.CashManagementTriggers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itriggersv1.cashmanagementtriggers(v=AX.60)
ms:contentKeyID: 47127997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITriggersV1.CashManagementTriggers
dev_langs:
- CSharp
- C++
- VB
---

# CashManagementTriggers Property

Gets the cash management triggers collection.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CashManagementTriggers As IEnumerable(Of ICashManagementTrigger)
    Get
'Usage
Dim instance As ITriggersV1
Dim value As IEnumerable(Of ICashManagementTrigger)

value = instance.CashManagementTriggers
```

``` csharp
IEnumerable<ICashManagementTrigger> CashManagementTriggers { get; }
```

``` c++
property IEnumerable<ICashManagementTrigger^>^ CashManagementTriggers {
    IEnumerable<ICashManagementTrigger^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ICashManagementTrigger](icashmanagementtrigger-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)\>  
The [System.Collections.Generic.IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ITriggersV1 Interface](itriggersv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

