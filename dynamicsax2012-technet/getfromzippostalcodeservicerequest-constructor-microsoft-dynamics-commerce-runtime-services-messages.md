---
title: GetFromZipPostalCodeServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetFromZipPostalCodeServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getfromzippostalcodeservicerequest.getfromzippostalcodeservicerequest(v=AX.60)
ms:contentKeyID: 65319588
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetFromZipPostalCodeServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetFromZipPostalCodeServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    countryRegionId As String, _
    zipPostalCode As String _
)
'Usage
Dim countryRegionId As String
Dim zipPostalCode As String

Dim instance As New GetFromZipPostalCodeServiceRequest(countryRegionId, _
    zipPostalCode)
```

``` csharp
public GetFromZipPostalCodeServiceRequest(
    string countryRegionId,
    string zipPostalCode
)
```

``` c++
public:
GetFromZipPostalCodeServiceRequest(
    String^ countryRegionId, 
    String^ zipPostalCode
)
```

#### Parameters

  - countryRegionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - zipPostalCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetFromZipPostalCodeServiceRequest Class](getfromzippostalcodeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

