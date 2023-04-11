---
title: ServiceResponse.RedirectUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: RedirectUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.RedirectUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceresponse.redirecturl(v=AX.60)
ms:contentKeyID: 65316333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.RedirectUrl
dev_langs:
- CSharp
- C++
- VB
---

# RedirectUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RedirectUrl As String
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As String

value = instance.RedirectUrl

instance.RedirectUrl = value
```

``` csharp
[DataMemberAttribute]
public string RedirectUrl { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RedirectUrl {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

