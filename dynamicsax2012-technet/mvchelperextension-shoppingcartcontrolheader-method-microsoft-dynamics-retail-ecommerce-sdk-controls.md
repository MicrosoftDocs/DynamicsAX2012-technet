---
title: MvcHelperExtension.ShoppingCartControlHeader Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: ShoppingCartControlHeader Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.ShoppingCartControlHeader(System.Web.Mvc.HtmlHelper,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.controls.mvchelperextension.shoppingcartcontrolheader(v=AX.60)
ms:contentKeyID: 65316987
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.ShoppingCartControlHeader
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartControlHeader Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function ShoppingCartControlHeader ( _
    htmlHelper As HtmlHelper, _
    checkoutUrl As String, _
    isMobileView As Boolean _
) As MvcHtmlString
'Usage
Dim htmlHelper As HtmlHelper
Dim checkoutUrl As String
Dim isMobileView As Boolean
Dim returnValue As MvcHtmlString

returnValue = htmlHelper.ShoppingCartControlHeader(checkoutUrl, _
    isMobileView)
```

``` csharp
public static MvcHtmlString ShoppingCartControlHeader(
    this HtmlHelper htmlHelper,
    string checkoutUrl,
    bool isMobileView
)
```

``` c++
[ExtensionAttribute]
public:
static MvcHtmlString^ ShoppingCartControlHeader(
    HtmlHelper^ htmlHelper, 
    String^ checkoutUrl, 
    bool isMobileView
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

#### Return Value

Type: MvcHtmlString  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type HtmlHelper. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[MvcHelperExtension Class](mvchelperextension-class-microsoft-dynamics-retail-ecommerce-sdk-controls.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls Namespace](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)

