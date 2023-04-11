---
title: StringResponse.Value Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StringResponse.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.stringresponse.value(v=AX.60)
ms:contentKeyID: 65318599
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.StringResponse.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Value As String
    Get
    Set
'Usage
Dim instance As StringResponse
Dim value As String

value = instance.Value

instance.Value = value
```

``` csharp
[DataMemberAttribute]
public string Value { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Value {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[StringResponse Class](stringresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

