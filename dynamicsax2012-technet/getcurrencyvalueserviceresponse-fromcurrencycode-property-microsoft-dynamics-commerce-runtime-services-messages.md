---
title: GetCurrencyValueServiceResponse.FromCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: FromCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.FromCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueserviceresponse.fromcurrencycode(v=AX.60)
ms:contentKeyID: 62211075
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceResponse.FromCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# FromCurrencyCode Property

Gets the currency code converted from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromCurrencyCode As String
    Get
    Private Set
'Usage
Dim instance As GetCurrencyValueServiceResponse
Dim value As String

value = instance.FromCurrencyCode
```

``` csharp
[DataMemberAttribute]
public string FromCurrencyCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ FromCurrencyCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetCurrencyValueServiceResponse Class](getcurrencyvalueserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

