---
title: ControlsSection.ProductUrlFormat Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: ProductUrlFormat Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.ProductUrlFormat
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.controlssection.producturlformat(v=AX.60)
ms:contentKeyID: 65317865
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.ControlsSection.ProductUrlFormat
dev_langs:
- CSharp
- C++
- VB
---

# ProductUrlFormat Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("productUrlFormat")> _
Public ReadOnly Property ProductUrlFormat As String
    Get
'Usage
Dim instance As ControlsSection
Dim value As String

value = instance.ProductUrlFormat
```

``` csharp
[ConfigurationPropertyAttribute("productUrlFormat")]
public string ProductUrlFormat { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"productUrlFormat")]
public:
property String^ ProductUrlFormat {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ControlsSection Class](controlssection-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

