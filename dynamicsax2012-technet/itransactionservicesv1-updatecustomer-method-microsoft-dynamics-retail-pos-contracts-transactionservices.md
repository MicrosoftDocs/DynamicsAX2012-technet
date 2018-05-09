---
title: ITransactionServicesV1.UpdateCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateCustomer(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.updatecustomer(v=AX.60)
ms:contentKeyID: 49822266
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method

**Note: This API is now obsolete.**

Updates existing customer in AX.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method has been deprecated. Use the ITransactionService::Invoke method instead")> _
Sub UpdateCustomer ( _
    ByRef retValue As Boolean, _
    ByRef comment As String, _
    ByRef customer As ICustomer _
)
'Usage
Dim instance As ITransactionServicesV1
Dim retValue As Boolean
Dim comment As String
Dim customer As ICustomer

instance.UpdateCustomer(retValue, comment, _
    customer)
```

``` csharp
[ObsoleteAttribute("This method has been deprecated. Use the ITransactionService::Invoke method instead")]
void UpdateCustomer(
    ref bool retValue,
    ref string comment,
    ref ICustomer customer
)
```

``` c++
[ObsoleteAttribute(L"This method has been deprecated. Use the ITransactionService::Invoke method instead")]
void UpdateCustomer(
    bool% retValue, 
    String^% comment, 
    ICustomer^% customer
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

