---
title: GetRoundedStringServiceRequest Constructor (Decimal, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetRoundedStringServiceRequest Constructor (Decimal, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.#ctor(System.Decimal,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringservicerequest.getroundedstringservicerequest(v=AX.60)
ms:contentKeyID: 65317617
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRoundedStringServiceRequest Constructor (Decimal, String, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    value As Decimal, _
    currencyCode As String, _
    isRounded As Boolean _
)
'Usage
Dim value As Decimal
Dim currencyCode As String
Dim isRounded As Boolean

Dim instance As New GetRoundedStringServiceRequest(value, currencyCode, _
    isRounded)
```

``` csharp
public GetRoundedStringServiceRequest(
    decimal value,
    string currencyCode,
    bool isRounded
)
```

``` c++
public:
GetRoundedStringServiceRequest(
    Decimal value, 
    String^ currencyCode, 
    bool isRounded
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isRounded  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetRoundedStringServiceRequest Class](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetRoundedStringServiceRequest Overload](getroundedstringservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

