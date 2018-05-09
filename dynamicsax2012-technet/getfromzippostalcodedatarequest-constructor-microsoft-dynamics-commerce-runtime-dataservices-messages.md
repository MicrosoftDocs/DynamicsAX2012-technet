---
title: GetFromZipPostalCodeDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetFromZipPostalCodeDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFromZipPostalCodeDataRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getfromzippostalcodedatarequest.getfromzippostalcodedatarequest(v=AX.60)
ms:contentKeyID: 65322098
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetFromZipPostalCodeDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetFromZipPostalCodeDataRequest Constructor

Initializes a new instance of the [GetFromZipPostalCodeDataRequest](getfromzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionCode As String, _
    zipCode As String _
)
'Usage
Dim countryRegionCode As String
Dim zipCode As String

Dim instance As New GetFromZipPostalCodeDataRequest(countryRegionCode, _
    zipCode)
```

``` csharp
public GetFromZipPostalCodeDataRequest(
    string countryRegionCode,
    string zipCode
)
```

``` c++
public:
GetFromZipPostalCodeDataRequest(
    String^ countryRegionCode, 
    String^ zipCode
)
```

#### Parameters

  - countryRegionCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - zipCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetFromZipPostalCodeDataRequest Class](getfromzippostalcodedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

