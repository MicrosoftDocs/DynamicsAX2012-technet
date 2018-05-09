---
title: Services.CheckoutServiceUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: CheckoutServiceUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.CheckoutServiceUrl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.services.checkoutserviceurl(v=AX.60)
ms:contentKeyID: 65315872
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.CheckoutServiceUrl
dev_langs:
- CSharp
- C++
- VB
---

# CheckoutServiceUrl Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("checkoutServiceUrl")> _
Public ReadOnly Property CheckoutServiceUrl As String
    Get
'Usage
Dim instance As Services
Dim value As String

value = instance.CheckoutServiceUrl
```

``` csharp
[ConfigurationPropertyAttribute("checkoutServiceUrl")]
public string CheckoutServiceUrl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"checkoutServiceUrl")]
public:
property String^ CheckoutServiceUrl {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Services Class](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

