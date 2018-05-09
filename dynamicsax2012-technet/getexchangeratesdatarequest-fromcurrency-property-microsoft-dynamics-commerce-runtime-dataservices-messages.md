---
title: GetExchangeRatesDataRequest.FromCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: FromCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.FromCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getexchangeratesdatarequest.fromcurrency(v=AX.60)
ms:contentKeyID: 65322674
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.FromCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FromCurrency Property

Gets the currency code from which to convert.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromCurrency As String
    Get
    Private Set
'Usage
Dim instance As GetExchangeRatesDataRequest
Dim value As String

value = instance.FromCurrency
```

``` csharp
[DataMemberAttribute]
public string FromCurrency { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ FromCurrency {
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

