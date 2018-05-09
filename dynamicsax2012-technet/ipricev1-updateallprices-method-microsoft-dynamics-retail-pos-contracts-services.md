---
title: IPriceV1.UpdateAllPrices Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UpdateAllPrices Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.UpdateAllPrices(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipricev1.updateallprices(v=AX.60)
ms:contentKeyID: 47344007
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.UpdateAllPrices
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAllPrices Method

To be used when a customer is specified or updated.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UpdateAllPrices ( _
    retailTransaction As IRetailTransaction, _
    restoreItemPrices As Boolean _
)
'Usage
Dim instance As IPriceV1
Dim retailTransaction As IRetailTransaction
Dim restoreItemPrices As Boolean

instance.UpdateAllPrices(retailTransaction, _
    restoreItemPrices)
```

``` csharp
void UpdateAllPrices(
    IRetailTransaction retailTransaction,
    bool restoreItemPrices
)
```

``` c++
void UpdateAllPrices(
    IRetailTransaction^ retailTransaction, 
    bool restoreItemPrices
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - restoreItemPrices  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPriceV1 Interface](ipricev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

