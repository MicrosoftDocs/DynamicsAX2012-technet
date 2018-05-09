---
title: ICustomerOrderTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ICustomerOrderTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerordertransaction(v=AX.60)
ms:contentKeyID: 47128874
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ICustomerOrderTransaction Interface

The ICustomerOrderTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("84B3161E-B29B-43E1-9064-DBE48A8564DC")> _
Public Interface ICustomerOrderTransaction _
    Inherits IRetailTransaction, IPosTransaction, IPosTransactionV1, IPosTransactionV2,  _
    IPosTransactionV3, IRetailTransactionV1, IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4,  _
    ICustomerOrderTransactionV1, ICustomerOrderTransactionV2, ICustomerOrderTransactionV3
'Usage
Dim instance As ICustomerOrderTransaction
```

``` csharp
[GuidAttribute("84B3161E-B29B-43E1-9064-DBE48A8564DC")]
public interface ICustomerOrderTransaction : IRetailTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, IRetailTransactionV1, 
    IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4, ICustomerOrderTransactionV1, ICustomerOrderTransactionV2, 
    ICustomerOrderTransactionV3
```

``` c++
[GuidAttribute(L"84B3161E-B29B-43E1-9064-DBE48A8564DC")]
public interface class ICustomerOrderTransaction : IRetailTransaction, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3, IRetailTransactionV1, 
    IRetailTransactionV2, IRetailTransactionV3, IRetailTransactionV4, ICustomerOrderTransactionV1, ICustomerOrderTransactionV2, 
    ICustomerOrderTransactionV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

