---
title: GetCustomerBalanceServiceResponse.Balance Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceResponse.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomerbalanceserviceresponse.balance(v=AX.60)
ms:contentKeyID: 62204952
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomerBalanceServiceResponse.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property

Gets the balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Balance As CustomerBalances
    Get
    Private Set
'Usage
Dim instance As GetCustomerBalanceServiceResponse
Dim value As CustomerBalances

value = instance.Balance
```

``` csharp
[DataMemberAttribute]
public CustomerBalances Balance { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CustomerBalances^ Balance {
    CustomerBalances^ get ();
    private: void set (CustomerBalances^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances](customerbalances-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The balance.  

## See Also

#### Reference

[GetCustomerBalanceServiceResponse Class](getcustomerbalanceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

