---
title: GetItemAvailableQuantitiesRequest.CustomerAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CustomerAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest.CustomerAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailablequantitiesrequest.customeraccountnumber(v=AX.60)
ms:contentKeyID: 49826209
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailableQuantitiesRequest.CustomerAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccountNumber As String
    Get
    Set
'Usage
Dim instance As GetItemAvailableQuantitiesRequest
Dim value As String

value = instance.CustomerAccountNumber

instance.CustomerAccountNumber = value
```

``` csharp
[DataMemberAttribute]
public string CustomerAccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer account number.  

## See Also

#### Reference

[GetItemAvailableQuantitiesRequest Class](getitemavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

