---
title: IssueGiftCardServiceRequest.Id Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issuegiftcardservicerequest.id(v=AX.60)
ms:contentKeyID: 62209250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueGiftCardServiceRequest.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property

Gets the gift card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Id As String
    Get
    Private Set
'Usage
Dim instance As IssueGiftCardServiceRequest
Dim value As String

value = instance.Id
```

``` csharp
[DataMemberAttribute]
public string Id { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Id {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IssueGiftCardServiceRequest Class](issuegiftcardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

