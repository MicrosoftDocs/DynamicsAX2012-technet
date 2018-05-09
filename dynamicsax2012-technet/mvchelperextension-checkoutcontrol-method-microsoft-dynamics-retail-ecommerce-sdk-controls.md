---
title: MvcHelperExtension.CheckoutControl Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: CheckoutControl Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.CheckoutControl(System.Web.Mvc.HtmlHelper,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.mvchelperextension.checkoutcontrol(v=AX.60)
ms:contentKeyID: 65316884
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.CheckoutControl
dev_langs:
- CSharp
- C++
- VB
---

# CheckoutControl Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function CheckoutControl ( _
    htmlHelper As HtmlHelper, _
    isMobileView As Boolean _
) As MvcHtmlString
'Usage
Dim htmlHelper As HtmlHelper
Dim isMobileView As Boolean
Dim returnValue As MvcHtmlString

returnValue = htmlHelper.CheckoutControl(isMobileView)
```

``` csharp
public static MvcHtmlString CheckoutControl(
    this HtmlHelper htmlHelper,
    bool isMobileView
)
```

``` c++
[ExtensionAttribute]
public:
static MvcHtmlString^ CheckoutControl(
    HtmlHelper^ htmlHelper, 
    bool isMobileView
)
```

#### Parameters

  - htmlHelper  
    Type: HtmlHelper  

<!-- end list -->

  - isMobileView  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: MvcHtmlString  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type HtmlHelper. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[MvcHelperExtension Class](mvchelperextension-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

