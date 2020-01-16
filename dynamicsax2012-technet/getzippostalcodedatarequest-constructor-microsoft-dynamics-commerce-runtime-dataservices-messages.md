---
title: GetZipPostalCodeDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetZipPostalCodeDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetZipPostalCodeDataRequest.#ctor(System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getzippostalcodedatarequest.getzippostalcodedatarequest(v=AX.60)
ms:contentKeyID: 65316722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetZipPostalCodeDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetZipPostalCodeDataRequest Constructor

Initializes a new instance of the [GetZipPostalCodeDataRequest](getzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    stateId As String, _
    countyId As String, _
    city As String, _
    district As String _
)
'Usage
Dim countryRegionCode As String
Dim stateId As String
Dim countyId As String
Dim city As String
Dim district As String

Dim instance As New GetZipPostalCodeDataRequest(countryRegionCode, _
    stateId, countyId, city, district)
```

``` csharp
public GetZipPostalCodeDataRequest(
    string countryRegionCode,
    string stateId,
    string countyId,
    string city,
    string district
)
```

``` c++
public:
GetZipPostalCodeDataRequest(
    String^ countryRegionCode, 
    String^ stateId, 
    String^ countyId, 
    String^ city, 
    String^ district
)
```

#### Parameters

  - countryRegionCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stateId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - countyId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - city  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - district  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetZipPostalCodeDataRequest Class](getzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

