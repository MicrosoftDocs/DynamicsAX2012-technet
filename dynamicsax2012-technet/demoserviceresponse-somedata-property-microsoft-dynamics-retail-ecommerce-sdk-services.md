---
title: DemoServiceResponse.SomeData Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SomeData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DemoServiceResponse.SomeData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.demoserviceresponse.somedata(v=AX.60)
ms:contentKeyID: 65318102
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DemoServiceResponse.SomeData
dev_langs:
- CSharp
- C++
- VB
---

# SomeData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SomeData As String
    Get
    Set
'Usage
Dim instance As DemoServiceResponse
Dim value As String

value = instance.SomeData

instance.SomeData = value
```

``` csharp
[DataMemberAttribute]
public string SomeData { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SomeData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DemoServiceResponse Class](demoserviceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

