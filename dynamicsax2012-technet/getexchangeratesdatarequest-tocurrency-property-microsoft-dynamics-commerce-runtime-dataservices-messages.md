---
title: GetExchangeRatesDataRequest.ToCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ToCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.ToCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getexchangeratesdatarequest.tocurrency(v=AX.60)
ms:contentKeyID: 65318587
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.ToCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ToCurrency Property

Gets the currency code to which to convert.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToCurrency As String
    Get
    Private Set
'Usage
Dim instance As GetExchangeRatesDataRequest
Dim value As String

value = instance.ToCurrency
```

``` csharp
[DataMemberAttribute]
public string ToCurrency { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ToCurrency {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetExchangeRatesDataRequest Class](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

