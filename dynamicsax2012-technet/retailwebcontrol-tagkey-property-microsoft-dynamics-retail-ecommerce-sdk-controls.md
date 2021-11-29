---
title: RetailWebControl.TagKey Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: TagKey Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.RetailWebControl.TagKey
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.retailwebcontrol.tagkey(v=AX.60)
ms:contentKeyID: 65318367
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.RetailWebControl.TagKey
dev_langs:
- CSharp
- C++
- VB
---

# TagKey Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [WebControl.TagKey](https://technet.microsoft.com/library/1k0x396z\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
Protected Overrides ReadOnly Property TagKey As HtmlTextWriterTag
    Get
'Usage
Dim value As HtmlTextWriterTag

value = Me.TagKey
```

``` csharp
protected override HtmlTextWriterTag TagKey { get; }
```

``` c++
protected:
virtual property HtmlTextWriterTag TagKey {
    HtmlTextWriterTag get () override;
}
```

#### Property Value

Type: [System.Web.UI.HtmlTextWriterTag](https://technet.microsoft.com/library/7760ezht\(v=ax.60\))  

## See Also

#### Reference

[RetailWebControl Class](retailwebcontrol-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

