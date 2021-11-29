---
title: ICustomerPaymentTransaction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ICustomerPaymentTransaction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerpaymenttransaction(v=AX.60)
ms:contentKeyID: 49832799
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerPaymentTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ICustomerPaymentTransaction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ICustomerPaymentTransaction interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("5ABD40BA-B27F-4B6A-A067-AED8A9CF74EE")> _
Public Interface ICustomerPaymentTransaction _
    Inherits ICustomerPaymentTransactionV1, IPosTransaction, IPosTransactionV1, IPosTransactionV2,  _
    IPosTransactionV3
'Usage
Dim instance As ICustomerPaymentTransaction
```

``` csharp
[GuidAttribute("5ABD40BA-B27F-4B6A-A067-AED8A9CF74EE")]
public interface ICustomerPaymentTransaction : ICustomerPaymentTransactionV1, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3
```

``` c++
[GuidAttribute(L"5ABD40BA-B27F-4B6A-A067-AED8A9CF74EE")]
public interface class ICustomerPaymentTransaction : ICustomerPaymentTransactionV1, 
    IPosTransaction, IPosTransactionV1, IPosTransactionV2, IPosTransactionV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

