---
title: ISalesOrderV1.SettleCustomerOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SettleCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SettleCustomerOrder(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.settlecustomerorder(v=AX.60)
ms:contentKeyID: 47344280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.SettleCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# SettleCustomerOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Settle sales order by invoicing the order for quantities picked-up.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SettleCustomerOrder ( _
    ByRef retValue As Boolean, _
    <OutAttribute> ByRef comment As String, _
    posTransaction As IRetailTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim retValue As Boolean
Dim comment As String
Dim posTransaction As IRetailTransaction

instance.SettleCustomerOrder(retValue, _
    comment, posTransaction)
```

``` csharp
void SettleCustomerOrder(
    ref bool retValue,
    out string comment,
    IRetailTransaction posTransaction
)
```

``` c++
void SettleCustomerOrder(
    bool% retValue, 
    [OutAttribute] String^% comment, 
    IRetailTransaction^ posTransaction
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

