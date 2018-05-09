---
title: GetDiscountCodesServiceRequest.Keyword Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Keyword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.Keyword
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesservicerequest.keyword(v=AX.60)
ms:contentKeyID: 62214704
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.Keyword
dev_langs:
- CSharp
- C++
- VB
---

# Keyword Property

Gets the search keyword.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keyword As String
    Get
    Private Set
'Usage
Dim instance As GetDiscountCodesServiceRequest
Dim value As String

value = instance.Keyword
```

``` csharp
[DataMemberAttribute]
public string Keyword { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Keyword {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetDiscountCodesServiceRequest Class](getdiscountcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

