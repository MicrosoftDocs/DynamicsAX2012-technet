---
title: GetCustomerBalanceServiceRequest Constructor (String, String, SearchLocation) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCustomerBalanceServiceRequest Constructor (String, String, SearchLocation)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerbalanceservicerequest.getcustomerbalanceservicerequest(v=AX.60)
ms:contentKeyID: 65319898
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomerBalanceServiceRequest Constructor (String, String, SearchLocation)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    accountNumber As String, _
    invoiceAccountNumber As String, _
    searchLocation As SearchLocation _
)
'Usage
Dim accountNumber As String
Dim invoiceAccountNumber As String
Dim searchLocation As SearchLocation

Dim instance As New GetCustomerBalanceServiceRequest(accountNumber, _
    invoiceAccountNumber, searchLocation)
```

``` csharp
public GetCustomerBalanceServiceRequest(
    string accountNumber,
    string invoiceAccountNumber,
    SearchLocation searchLocation
)
```

``` c++
public:
GetCustomerBalanceServiceRequest(
    String^ accountNumber, 
    String^ invoiceAccountNumber, 
    SearchLocation searchLocation
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - searchLocation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation](searchlocation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetCustomerBalanceServiceRequest Class](getcustomerbalanceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCustomerBalanceServiceRequest Overload](getcustomerbalanceservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

