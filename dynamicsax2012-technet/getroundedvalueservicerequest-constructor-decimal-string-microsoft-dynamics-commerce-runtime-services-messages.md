---
title: GetRoundedValueServiceRequest Constructor (Decimal, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetRoundedValueServiceRequest Constructor (Decimal, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedValueServiceRequest.#ctor(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedvalueservicerequest.getroundedvalueservicerequest(v=AX.60)
ms:contentKeyID: 65319195
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRoundedValueServiceRequest Constructor (Decimal, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    value As Decimal, _
    currencyCode As String _
)
'Usage
Dim value As Decimal
Dim currencyCode As String

Dim instance As New GetRoundedValueServiceRequest(value, currencyCode)
```

``` csharp
public GetRoundedValueServiceRequest(
    decimal value,
    string currencyCode
)
```

``` c++
public:
GetRoundedValueServiceRequest(
    Decimal value, 
    String^ currencyCode
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetRoundedValueServiceRequest Class](getroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetRoundedValueServiceRequest Overload](getroundedvalueservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

