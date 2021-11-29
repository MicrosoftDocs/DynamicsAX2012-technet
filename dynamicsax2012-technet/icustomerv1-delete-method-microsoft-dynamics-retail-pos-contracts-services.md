---
title: ICustomerV1.Delete Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Delete Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Delete(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.delete(v=AX.60)
ms:contentKeyID: 47343963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Delete
dev_langs:
- CSharp
- C++
- VB
---

# Delete Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Delete the customer from the database if the customer holds no customer transactions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Delete ( _
    customerId As String _
) As Boolean
'Usage
Dim instance As ICustomerV1
Dim customerId As String
Dim returnValue As Boolean

returnValue = instance.Delete(customerId)
```

``` csharp
bool Delete(
    string customerId
)
```

``` c++
bool Delete(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if operations is successful  

## Remarks

This method is not implemented

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

