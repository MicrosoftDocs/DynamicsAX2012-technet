---
title: GetDiscountCodesServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDiscountCodesServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.#ctor(System.String,System.String,System.String,System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesservicerequest.getdiscountcodesservicerequest(v=AX.60)
ms:contentKeyID: 65321876
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodesServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    offerId As String, _
    discountCode As String, _
    keyword As String, _
    activeDate As DateTime, _
    settings As QueryResultSettings _
)
'Usage
Dim offerId As String
Dim discountCode As String
Dim keyword As String
Dim activeDate As DateTime
Dim settings As QueryResultSettings

Dim instance As New GetDiscountCodesServiceRequest(offerId, _
    discountCode, keyword, activeDate, _
    settings)
```

``` csharp
public GetDiscountCodesServiceRequest(
    string offerId,
    string discountCode,
    string keyword,
    DateTime activeDate,
    QueryResultSettings settings
)
```

``` c++
public:
GetDiscountCodesServiceRequest(
    String^ offerId, 
    String^ discountCode, 
    String^ keyword, 
    DateTime activeDate, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - keyword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDiscountCodesServiceRequest Class](getdiscountcodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

