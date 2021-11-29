---
title: GetRoundedStringServiceRequest Constructor (Decimal, String, Int32, Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetRoundedStringServiceRequest Constructor (Decimal, String, Int32, Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.#ctor(System.Decimal,System.String,System.Int32,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringservicerequest.getroundedstringservicerequest(v=AX.60)
ms:contentKeyID: 65320546
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRoundedStringServiceRequest Constructor (Decimal, String, Int32, Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    value As Decimal, _
    currencyCode As String, _
    numberOfDecimals As Integer, _
    useSalesRounding As Boolean, _
    isRounded As Boolean _
)
'Usage
Dim value As Decimal
Dim currencyCode As String
Dim numberOfDecimals As Integer
Dim useSalesRounding As Boolean
Dim isRounded As Boolean

Dim instance As New GetRoundedStringServiceRequest(value, currencyCode, _
    numberOfDecimals, useSalesRounding, _
    isRounded)
```

``` csharp
public GetRoundedStringServiceRequest(
    decimal value,
    string currencyCode,
    int numberOfDecimals,
    bool useSalesRounding,
    bool isRounded
)
```

``` c++
public:
GetRoundedStringServiceRequest(
    Decimal value, 
    String^ currencyCode, 
    int numberOfDecimals, 
    bool useSalesRounding, 
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

  - numberOfDecimals  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - useSalesRounding  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - isRounded  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetRoundedStringServiceRequest Class](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetRoundedStringServiceRequest Overload](getroundedstringservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

