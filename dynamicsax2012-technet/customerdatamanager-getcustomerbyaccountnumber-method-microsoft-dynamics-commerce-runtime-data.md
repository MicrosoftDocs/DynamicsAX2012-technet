---
title: CustomerDataManager.GetCustomerByAccountNumber Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCustomerByAccountNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByAccountNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.getcustomerbyaccountnumber(v=AX.60)
ms:contentKeyID: 62205540
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.GetCustomerByAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByAccountNumber Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer by acccount number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerByAccountNumber ( _
    accountNumber As String _
) As Customer
'Usage
Dim instance As CustomerDataManager
Dim accountNumber As String
Dim returnValue As Customer

returnValue = instance.GetCustomerByAccountNumber(accountNumber)
```

``` csharp
public Customer GetCustomerByAccountNumber(
    string accountNumber
)
```

``` c++
public:
Customer^ GetCustomerByAccountNumber(
    String^ accountNumber
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

