---
title: ResponseError.Source Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.responseerror.source(v=AX.60)
ms:contentKeyID: 65317773
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Source As String
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As String

value = instance.Source

instance.Source = value
```

``` csharp
[DataMemberAttribute]
public string Source { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Source {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

