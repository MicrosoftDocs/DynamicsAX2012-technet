---
title: ICashChangerV1.InsertedAmount Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: InsertedAmount Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.InsertedAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.insertedamount(v=AX.60)
ms:contentKeyID: 47344037
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.InsertedAmount
dev_langs:
- CSharp
- C++
- VB
---

# InsertedAmount Event

Initiates inserted amount event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event InsertedAmount As InsertedAmountDelegate
'Usage
Dim instance As ICashChangerV1
Dim handler As InsertedAmountDelegate

AddHandler instance.InsertedAmount, handler
```

``` csharp
event InsertedAmountDelegate InsertedAmount
```

``` c++
 event InsertedAmountDelegate^ InsertedAmount {
    void add (InsertedAmountDelegate^ value);
    void remove (InsertedAmountDelegate^ value);
}
```

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

