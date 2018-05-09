---
title: ICustomerV1.Update Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Update Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Update(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.update(v=AX.60)
ms:contentKeyID: 47344406
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.Update
dev_langs:
- CSharp
- C++
- VB
---

# Update Method

**Note: This API is now obsolete.**

Updates the customer information in the database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method is not used anymore. Please use the new Update method which returns an ICustomer object")> _
Function Update ( _
    customerId As String _
) As Boolean
'Usage
Dim instance As ICustomerV1
Dim customerId As String
Dim returnValue As Boolean

returnValue = instance.Update(customerId)
```

``` csharp
[ObsoleteAttribute("This method is not used anymore. Please use the new Update method which returns an ICustomer object")]
bool Update(
    string customerId
)
```

``` c++
[ObsoleteAttribute(L"This method is not used anymore. Please use the new Update method which returns an ICustomer object")]
bool Update(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if operations is successful; otherwise, false.  

## Remarks

This method is not implemented.

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

