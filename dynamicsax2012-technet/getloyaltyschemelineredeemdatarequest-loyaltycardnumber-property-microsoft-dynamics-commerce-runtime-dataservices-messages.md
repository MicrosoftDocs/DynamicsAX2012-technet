---
title: GetLoyaltySchemeLineRedeemDataRequest.LoyaltyCardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LoyaltyCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest.LoyaltyCardNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getloyaltyschemelineredeemdatarequest.loyaltycardnumber(v=AX.60)
ms:contentKeyID: 65321919
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLoyaltySchemeLineRedeemDataRequest.LoyaltyCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardNumber Property

Gets the loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardNumber As String
    Get
    Private Set
'Usage
Dim instance As GetLoyaltySchemeLineRedeemDataRequest
Dim value As String

value = instance.LoyaltyCardNumber
```

``` csharp
[DataMemberAttribute]
public string LoyaltyCardNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LoyaltyCardNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetLoyaltySchemeLineRedeemDataRequest Class](getloyaltyschemelineredeemdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

