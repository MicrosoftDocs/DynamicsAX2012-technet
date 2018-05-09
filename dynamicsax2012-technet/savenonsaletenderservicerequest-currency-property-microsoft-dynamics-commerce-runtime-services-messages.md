---
title: SaveNonSaleTenderServiceRequest.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest.Currency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.savenonsaletenderservicerequest.currency(v=AX.60)
ms:contentKeyID: 62210408
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveNonSaleTenderServiceRequest.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property

Gets or sets the currency of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Set
'Usage
Dim instance As SaveNonSaleTenderServiceRequest
Dim value As String

value = instance.Currency

instance.Currency = value
```

``` csharp
[DataMemberAttribute]
public string Currency { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Currency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveNonSaleTenderServiceRequest Class](savenonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

