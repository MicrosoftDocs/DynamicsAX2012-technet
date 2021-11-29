---
title: ITransactionServicesV1.CreateAddress Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: CreateAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.CreateAddress(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartyAddressRelationship@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartyAddressRelationshipMapping@,System.Collections.Generic.IList{System.Int64}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.createaddress(v=AX.60)
ms:contentKeyID: 47128593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.CreateAddress
dev_langs:
- CSharp
- C++
- VB
---

# CreateAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new address associated with the customer. The new address's RecId is returned in the ID property of the address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CreateAddress ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef customer As ICustomer, _
    ByRef address As IAddress, _
    ByRef addressRelationship As IDirPartyAddressRelationship, _
    ByRef addressRelationshipMapping As IDirPartyAddressRelationshipMapping, _
    ByRef entityKeys As IList(Of Long) _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim customer As ICustomer
Dim address As IAddress
Dim addressRelationship As IDirPartyAddressRelationship
Dim addressRelationshipMapping As IDirPartyAddressRelationshipMapping
Dim entityKeys As IList(Of Long)

instance.CreateAddress(retValue, comment, _
    customer, address, addressRelationship, _
    addressRelationshipMapping, entityKeys)
```

``` csharp
void CreateAddress(
    ref bool retValue,
    ref string comment,
    ref ICustomer customer,
    ref IAddress address,
    ref IDirPartyAddressRelationship addressRelationship,
    ref IDirPartyAddressRelationshipMapping addressRelationshipMapping,
    ref IList<long> entityKeys
)
```

``` c++
void CreateAddress(
    bool% retValue, 
    String^% comment, 
    ICustomer^% customer, 
    IAddress^% address, 
    IDirPartyAddressRelationship^% addressRelationship, 
    IDirPartyAddressRelationshipMapping^% addressRelationshipMapping, 
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

  - address  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - addressRelationship  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartyAddressRelationship](idirpartyaddressrelationship-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - addressRelationshipMapping  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDirPartyAddressRelationshipMapping](idirpartyaddressrelationshipmapping-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - entityKeys  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

