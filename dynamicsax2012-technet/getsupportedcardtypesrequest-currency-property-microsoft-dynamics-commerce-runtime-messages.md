---
title: GetSupportedCardTypesRequest.Currency Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Currency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedCardTypesRequest.Currency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getsupportedcardtypesrequest.currency(v=AX.60)
ms:contentKeyID: 49821775
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetSupportedCardTypesRequest.Currency
dev_langs:
- CSharp
- C++
- VB
---

# Currency Property

Gets or sets the currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Currency As String
    Get
    Set
'Usage
Dim instance As GetSupportedCardTypesRequest
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
The currency.  

## See Also

#### Reference

[GetSupportedCardTypesRequest Class](getsupportedcardtypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

