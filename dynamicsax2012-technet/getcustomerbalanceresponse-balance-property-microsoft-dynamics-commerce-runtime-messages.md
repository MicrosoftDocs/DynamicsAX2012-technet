---
title: GetCustomerBalanceResponse.Balance Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Balance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceResponse.Balance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomerbalanceresponse.balance(v=AX.60)
ms:contentKeyID: 62206163
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerBalanceResponse.Balance
dev_langs:
- CSharp
- C++
- VB
---

# Balance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Balance As CustomerBalances
    Get
    Private Set
'Usage
Dim instance As GetCustomerBalanceResponse
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

[GetCustomerBalanceResponse Class](getcustomerbalanceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

