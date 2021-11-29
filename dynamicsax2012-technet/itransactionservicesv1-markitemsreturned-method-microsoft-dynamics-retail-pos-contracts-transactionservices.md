---
title: ITransactionServicesV1.MarkItemsReturned Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: MarkItemsReturned Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.MarkItemsReturned(System.Boolean@,System.String@,System.String[]@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITSMarkItemReturned[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.markitemsreturned(v=AX.60)
ms:contentKeyID: 47129146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.MarkItemsReturned
dev_langs:
- CSharp
- C++
- VB
---

# MarkItemsReturned Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub MarkItemsReturned ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef errorMessages As String(), _
    returnedItems As ITSMarkItemReturned() _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim errorMessages As String()
Dim returnedItems As ITSMarkItemReturned()

instance.MarkItemsReturned(retValue, _
    comment, errorMessages, returnedItems)
```

``` csharp
void MarkItemsReturned(
    ref bool retValue,
    ref string comment,
    ref string[] errorMessages,
    ITSMarkItemReturned[] returnedItems
)
```

``` c++
void MarkItemsReturned(
    bool% retValue, 
    String^% comment, 
    array<String^>^% errorMessages, 
    array<ITSMarkItemReturned^>^ returnedItems
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - errorMessages  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - returnedItems  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITSMarkItemReturned](itsmarkitemreturned-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\[\]  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

