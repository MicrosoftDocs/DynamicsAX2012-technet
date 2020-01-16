---
title: IssueOrAddToGiftCardRequest.CurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.issueoraddtogiftcardrequest.currencycode(v=AX.60)
ms:contentKeyID: 62214977
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.IssueOrAddToGiftCardRequest.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property

Gets the gift card currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CurrencyCode As String
    Get
    Private Set
'Usage
Dim instance As IssueOrAddToGiftCardRequest
Dim value As String

value = instance.CurrencyCode
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string CurrencyCode { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ CurrencyCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IssueOrAddToGiftCardRequest Class](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

