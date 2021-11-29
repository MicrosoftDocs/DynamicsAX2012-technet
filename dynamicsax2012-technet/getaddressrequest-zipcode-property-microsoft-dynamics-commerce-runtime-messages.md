---
title: GetAddressRequest.ZipCode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ZipCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.ZipCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.zipcode(v=AX.60)
ms:contentKeyID: 65317656
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.ZipCode
dev_langs:
- CSharp
- C++
- VB
---

# ZipCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ZipCode As String
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As String

value = instance.ZipCode

instance.ZipCode = value
```

``` csharp
[DataMemberAttribute]
public string ZipCode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ZipCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetAddressRequest Class](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

