---
title: Services.CustomerServiceUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: CustomerServiceUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.CustomerServiceUrl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.services.customerserviceurl(v=AX.60)
ms:contentKeyID: 65315591
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.CustomerServiceUrl
dev_langs:
- CSharp
- C++
- VB
---

# CustomerServiceUrl Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("customerServiceUrl")> _
Public ReadOnly Property CustomerServiceUrl As String
    Get
'Usage
Dim instance As Services
Dim value As String

value = instance.CustomerServiceUrl
```

``` csharp
[ConfigurationPropertyAttribute("customerServiceUrl")]
public string CustomerServiceUrl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"customerServiceUrl")]
public:
property String^ CustomerServiceUrl {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Services Class](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

