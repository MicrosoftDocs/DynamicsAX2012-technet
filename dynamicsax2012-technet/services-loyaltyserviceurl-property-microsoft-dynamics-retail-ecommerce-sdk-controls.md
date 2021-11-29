---
title: Services.LoyaltyServiceUrl Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: LoyaltyServiceUrl Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.LoyaltyServiceUrl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.services.loyaltyserviceurl(v=AX.60)
ms:contentKeyID: 65317135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services.LoyaltyServiceUrl
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyServiceUrl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("loyaltyServiceUrl")> _
Public ReadOnly Property LoyaltyServiceUrl As String
    Get
'Usage
Dim instance As Services
Dim value As String

value = instance.LoyaltyServiceUrl
```

``` csharp
[ConfigurationPropertyAttribute("loyaltyServiceUrl")]
public string LoyaltyServiceUrl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"loyaltyServiceUrl")]
public:
property String^ LoyaltyServiceUrl {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Services Class](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

