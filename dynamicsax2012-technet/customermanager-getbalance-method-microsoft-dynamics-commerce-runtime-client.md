---
title: CustomerManager.GetBalance Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetBalance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetBalance(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.getbalance(v=AX.60)
ms:contentKeyID: 65322051
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.GetBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetBalance Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetBalance ( _
    accountNumber As String, _
    invoiceAccountNumber As String, _
    searchLocation As SearchLocation _
) As CustomerBalances
'Usage
Dim instance As CustomerManager
Dim accountNumber As String
Dim invoiceAccountNumber As String
Dim searchLocation As SearchLocation
Dim returnValue As CustomerBalances

returnValue = instance.GetBalance(accountNumber, _
    invoiceAccountNumber, searchLocation)
```

``` csharp
public CustomerBalances GetBalance(
    string accountNumber,
    string invoiceAccountNumber,
    SearchLocation searchLocation
)
```

``` c++
public:
CustomerBalances^ GetBalance(
    String^ accountNumber, 
    String^ invoiceAccountNumber, 
    SearchLocation searchLocation
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - searchLocation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation](searchlocation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances](customerbalances-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

