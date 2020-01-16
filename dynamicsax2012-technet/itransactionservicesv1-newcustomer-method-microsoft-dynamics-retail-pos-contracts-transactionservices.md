---
title: ITransactionServicesV1.NewCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: NewCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.NewCustomer(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer@,System.Int64,System.Collections.Generic.IList{System.Int64}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.newcustomer(v=AX.60)
ms:contentKeyID: 47128846
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.NewCustomer
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomer Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub NewCustomer ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef customer As ICustomer, _
    storeRecId As Long, _
    ByRef entityKeys As IList(Of Long) _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim customer As ICustomer
Dim storeRecId As Long
Dim entityKeys As IList(Of Long)

instance.NewCustomer(retValue, comment, _
    customer, storeRecId, entityKeys)
```

``` csharp
void NewCustomer(
    ref bool retValue,
    ref string comment,
    ref ICustomer customer,
    long storeRecId,
    ref IList<long> entityKeys
)
```

``` c++
void NewCustomer(
    bool% retValue, 
    String^% comment, 
    ICustomer^% customer, 
    long long storeRecId, 
    IList<long long>^% entityKeys
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - storeRecId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - entityKeys  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

