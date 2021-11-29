---
title: Services.ShoppingCartServiceUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: ShoppingCartServiceUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.ShoppingCartServiceUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.services.shoppingcartserviceurl(v=AX.60)
ms:contentKeyID: 65317320
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.ShoppingCartServiceUrl
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartServiceUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("shoppingCartServiceUrl")> _
Public ReadOnly Property ShoppingCartServiceUrl As String
    Get
'Usage
Dim instance As Services
Dim value As String

value = instance.ShoppingCartServiceUrl
```

``` csharp
[ConfigurationPropertyAttribute("shoppingCartServiceUrl")]
public string ShoppingCartServiceUrl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"shoppingCartServiceUrl")]
public:
property String^ ShoppingCartServiceUrl {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Services Class](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

