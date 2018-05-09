---
title: GetDiscountCodesDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetDiscountCodesDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountCodesDataServiceRequest.#ctor(System.String,System.String,System.String,System.DateTime,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getdiscountcodesdataservicerequest.getdiscountcodesdataservicerequest(v=AX.60)
ms:contentKeyID: 65323124
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetDiscountCodesDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodesDataServiceRequest Constructor

Initializes a new instance of the [GetDiscountCodesDataServiceRequest](getdiscountcodesdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

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

Dim instance As New GetDiscountCodesDataServiceRequest(offerId, _
    discountCode, keyword, activeDate, _
    settings)
```

``` csharp
public GetDiscountCodesDataServiceRequest(
    string offerId,
    string discountCode,
    string keyword,
    DateTime activeDate,
    QueryResultSettings settings
)
```

``` c++
public:
GetDiscountCodesDataServiceRequest(
    String^ offerId, 
    String^ discountCode, 
    String^ keyword, 
    DateTime activeDate, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - keyword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetDiscountCodesDataServiceRequest Class](getdiscountcodesdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

