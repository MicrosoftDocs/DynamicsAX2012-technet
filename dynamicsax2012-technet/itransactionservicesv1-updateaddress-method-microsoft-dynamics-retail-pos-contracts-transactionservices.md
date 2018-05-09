---
title: ITransactionServicesV1.UpdateAddress Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: UpdateAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateAddress(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress@,System.Collections.Generic.IList{System.Int64}@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.updateaddress(v=AX.60)
ms:contentKeyID: 47128453
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateAddress
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAddress Method

Updates the address indicated by the ID property (which maps to the Microsoft Dynamics AX RecId) of the address parameter.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UpdateAddress ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef address As IAddress, _
    ByRef entityKeys As IList(Of Long) _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim address As IAddress
Dim entityKeys As IList(Of Long)

instance.UpdateAddress(retValue, comment, _
    address, entityKeys)
```

``` csharp
void UpdateAddress(
    ref bool retValue,
    ref string comment,
    ref IAddress address,
    ref IList<long> entityKeys
)
```

``` c++
void UpdateAddress(
    bool% retValue, 
    String^% comment, 
    IAddress^% address, 
    IList<long long>^% entityKeys
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - address  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - entityKeys  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

