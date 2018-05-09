---
title: GetCustomersProcedure.GetCustomerByAccountNumber Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices)
TOCTitle: GetCustomerByAccountNumber Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices.GetCustomersProcedure.GetCustomerByAccountNumber(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.dataservices.getcustomersprocedure.getcustomerbyaccountnumber(v=AX.60)
ms:contentKeyID: 65322129
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices.GetCustomersProcedure.GetCustomerByAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerByAccountNumber Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices](microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerByAccountNumber ( _
    accountNumber As String _
) As Customer
'Usage
Dim instance As GetCustomersProcedure
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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCustomersProcedure Class](getcustomersprocedure-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.DataServices Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-dataservices-namespace.md)

