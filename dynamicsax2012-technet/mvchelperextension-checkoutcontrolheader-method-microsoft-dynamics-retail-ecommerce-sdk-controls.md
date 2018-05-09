---
title: MvcHelperExtension.CheckoutControlHeader Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls)
TOCTitle: CheckoutControlHeader Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.CheckoutControlHeader(System.Web.Mvc.HtmlHelper,System.String,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.controls.mvchelperextension.checkoutcontrolheader(v=AX.60)
ms:contentKeyID: 65317776
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.MvcHelperExtension.CheckoutControlHeader
dev_langs:
- CSharp
- C++
- VB
---

# CheckoutControlHeader Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls](microsoft-dynamics-retail-ecommerce-sdk-controls-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Controls.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function CheckoutControlHeader ( _
    htmlHelper As HtmlHelper, _
    orderConfirmationUrl As String, _
    hasInventoryCheck As Boolean, _
    isMobileView As Boolean _
) As MvcHtmlString
'Usage
Dim htmlHelper As HtmlHelper
Dim orderConfirmationUrl As String
Dim hasInventoryCheck As Boolean
Dim isMobileView As Boolean
Dim returnValue As MvcHtmlString

returnValue = htmlHelper.CheckoutControlHeader(orderConfirmationUrl, _
    hasInventoryCheck, isMobileView)
```

``` csharp
public static MvcHtmlString CheckoutControlHeader(
    this HtmlHelper htmlHelper,
    string orderConfirmationUrl,
    bool hasInventoryCheck,
    bool isMobileView
)
```

``` c++
[ExtensionAttribute]
public:
static MvcHtmlString^ CheckoutControlHeader(
    HtmlHelper^ htmlHelper, 
    String^ orderConfirmationUrl, 
    bool hasInventoryCheck, 
    bool isMobileView
)
```

#### Parameters

  - htmlHelper  
    Type: HtmlHelper  

<!-- end list -->

  - orderConfirmationUrl  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - hasInventoryCheck  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

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

