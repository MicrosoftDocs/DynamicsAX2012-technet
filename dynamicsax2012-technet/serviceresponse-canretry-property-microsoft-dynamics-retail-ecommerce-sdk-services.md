---
title: ServiceResponse.CanRetry Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CanRetry Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.CanRetry
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceresponse.canretry(v=AX.60)
ms:contentKeyID: 65316830
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceResponse.CanRetry
dev_langs:
- CSharp
- C++
- VB
---

# CanRetry Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CanRetry As Boolean
    Get
    Set
'Usage
Dim instance As ServiceResponse
Dim value As Boolean

value = instance.CanRetry

instance.CanRetry = value
```

``` csharp
[DataMemberAttribute]
public bool CanRetry { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool CanRetry {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

