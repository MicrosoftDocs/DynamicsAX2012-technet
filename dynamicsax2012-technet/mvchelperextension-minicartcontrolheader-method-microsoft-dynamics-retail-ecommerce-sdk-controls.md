---
title: MvcHelperExtension.MiniCartControlHeader Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: MiniCartControlHeader Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.MiniCartControlHeader(System.Web.Mvc.HtmlHelper,System.String,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.mvchelperextension.minicartcontrolheader(v=AX.60)
ms:contentKeyID: 65318159
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.MiniCartControlHeader
dev_langs:
- CSharp
- C++
- VB
---

# MiniCartControlHeader Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function MiniCartControlHeader ( _
    htmlHelper As HtmlHelper, _
    checkoutUrl As String, _
    isMobileView As Boolean, _
    isCheckoutCart As Boolean _
) As MvcHtmlString
'Usage
Dim htmlHelper As HtmlHelper
Dim checkoutUrl As String
Dim isMobileView As Boolean
Dim isCheckoutCart As Boolean
Dim returnValue As MvcHtmlString

returnValue = htmlHelper.MiniCartControlHeader(checkoutUrl, _
    isMobileView, isCheckoutCart)
```

``` csharp
public static MvcHtmlString MiniCartControlHeader(
    this HtmlHelper htmlHelper,
    string checkoutUrl,
    bool isMobileView,
    bool isCheckoutCart
)
```

``` c++
[ExtensionAttribute]
public:
static MvcHtmlString^ MiniCartControlHeader(
    HtmlHelper^ htmlHelper, 
    String^ checkoutUrl, 
    bool isMobileView, 
    bool isCheckoutCart
)
```

#### Parameters

  - htmlHelper  
    Type: HtmlHelper  

<!-- end list -->

  - checkoutUrl  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isMobileView  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - isCheckoutCart  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: MvcHtmlString  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type HtmlHelper. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[MvcHelperExtension Class](mvchelperextension-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

