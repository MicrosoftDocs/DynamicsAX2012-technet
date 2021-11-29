---
title: ISalesOrderV1.CreateCustomerOrder Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CreateCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CreateCustomerOrder(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.createcustomerorder(v=AX.60)
ms:contentKeyID: 47344214
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CreateCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# CreateCustomerOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new sales order in AX.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CreateCustomerOrder ( _
    ByRef retValue As Boolean, _
    <OutAttribute> ByRef comment As String, _
    posTransaction As IRetailTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim retValue As Boolean
Dim comment As String
Dim posTransaction As IRetailTransaction

instance.CreateCustomerOrder(retValue, _
    comment, posTransaction)
```

``` csharp
void CreateCustomerOrder(
    ref bool retValue,
    out string comment,
    IRetailTransaction posTransaction
)
```

``` c++
void CreateCustomerOrder(
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

