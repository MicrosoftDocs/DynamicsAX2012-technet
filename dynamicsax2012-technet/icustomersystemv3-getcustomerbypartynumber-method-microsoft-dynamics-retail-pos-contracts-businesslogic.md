---
title: ICustomerSystemV3.GetCustomerByPartyNumber Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetCustomerByPartyNumber Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.GetCustomerByPartyNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv3.getcustomerbypartynumber(v=AX.60)
ms:contentKeyID: 62202021
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.GetCustomerByPartyNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByPartyNumber Method

Gets the customer by party number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetCustomerByPartyNumber ( _
    partyNumber As String _
) As ICustomer
'Usage
Dim instance As ICustomerSystemV3
Dim partyNumber As String
Dim returnValue As ICustomer

returnValue = instance.GetCustomerByPartyNumber(partyNumber)
```

``` csharp
ICustomer GetCustomerByPartyNumber(
    string partyNumber
)
```

``` c++
ICustomer^ GetCustomerByPartyNumber(
    String^ partyNumber
)
```

#### Parameters

  - partyNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerSystemV3 Interface](icustomersystemv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

