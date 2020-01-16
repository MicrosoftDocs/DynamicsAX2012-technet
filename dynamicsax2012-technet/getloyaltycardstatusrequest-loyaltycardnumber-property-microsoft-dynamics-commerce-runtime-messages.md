---
title: GetLoyaltyCardStatusRequest.LoyaltyCardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LoyaltyCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardStatusRequest.LoyaltyCardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getloyaltycardstatusrequest.loyaltycardnumber(v=AX.60)
ms:contentKeyID: 62206552
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLoyaltyCardStatusRequest.LoyaltyCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardNumber Property

Gets or sets the loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardNumber As String
    Get
    Set
'Usage
Dim instance As GetLoyaltyCardStatusRequest
Dim value As String

value = instance.LoyaltyCardNumber

instance.LoyaltyCardNumber = value
```

``` csharp
[DataMemberAttribute]
public string LoyaltyCardNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LoyaltyCardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltyCardStatusRequest Class](getloyaltycardstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

