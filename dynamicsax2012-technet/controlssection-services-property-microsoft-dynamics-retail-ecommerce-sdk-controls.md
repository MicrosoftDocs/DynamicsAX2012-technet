---
title: ControlsSection.Services Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: Services Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.Services
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.controlssection.services(v=AX.60)
ms:contentKeyID: 65317266
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.Services
dev_langs:
- CSharp
- C++
- VB
---

# Services Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("services")> _
Public ReadOnly Property Services As Services
    Get
'Usage
Dim instance As ControlsSection
Dim value As Services

value = instance.Services
```

``` csharp
[ConfigurationPropertyAttribute("services")]
public Services Services { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"services")]
public:
property Services^ Services {
    Services^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.Services](services-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)  

## See Also

#### Reference

[ControlsSection Class](controlssection-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

