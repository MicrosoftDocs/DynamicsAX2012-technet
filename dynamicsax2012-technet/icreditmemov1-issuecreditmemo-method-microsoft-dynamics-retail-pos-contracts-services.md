---
title: ICreditMemoV1.IssueCreditMemo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IssueCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.IssueCreditMemo(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICreditMemoTenderLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icreditmemov1.issuecreditmemo(v=AX.60)
ms:contentKeyID: 47344293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICreditMemoV1.IssueCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# IssueCreditMemo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Issue credit memo, issues a gift certificate and adds it to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub IssueCreditMemo ( _
    creditMemoItem As ICreditMemoTenderLineItem, _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ICreditMemoV1
Dim creditMemoItem As ICreditMemoTenderLineItem
Dim retailTransaction As IRetailTransaction

instance.IssueCreditMemo(creditMemoItem, _
    retailTransaction)
```

``` csharp
void IssueCreditMemo(
    ICreditMemoTenderLineItem creditMemoItem,
    IRetailTransaction retailTransaction
)
```

``` c++
void IssueCreditMemo(
    ICreditMemoTenderLineItem^ creditMemoItem, 
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - creditMemoItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICreditMemoTenderLineItem](icreditmemotenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICreditMemoV1 Interface](icreditmemov1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

