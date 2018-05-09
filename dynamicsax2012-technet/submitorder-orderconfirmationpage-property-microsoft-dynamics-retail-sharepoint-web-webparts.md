---
title: SubmitOrder.OrderConfirmationPage Property  (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: OrderConfirmationPage Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.SubmitOrder.OrderConfirmationPage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.webparts.submitorder.orderconfirmationpage(v=AX.60)
ms:contentKeyID: 62207163
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.SubmitOrder.OrderConfirmationPage
dev_langs:
- CSharp
- C++
- VB
---

# OrderConfirmationPage Property

Gets or sets the confirmation page to redirect to upon successful order submission.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<LocalizedCategoryAttribute("Order Settings")> _
<WebBrowsableAttribute(True)> _
<LocalizedWebDescriptionAttribute("SubmitOrderWebDescriptionOrderConfirmation")> _
<WebPartStorageAttribute(Storage.Shared)> _
<PersonalizableAttribute(PersonalizationScope.Shared)> _
<LocalizedWebDisplayNameAttribute("SubmitOrderWebDisplayNameOrderConfirmation")> _
Public Property OrderConfirmationPage As String
    Get
    Set
'Usage
Dim instance As SubmitOrder
Dim value As String

value = instance.OrderConfirmationPage

instance.OrderConfirmationPage = value
```

``` csharp
[LocalizedCategoryAttribute("Order Settings")]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute("SubmitOrderWebDescriptionOrderConfirmation")]
[WebPartStorageAttribute(Storage.Shared)]
[PersonalizableAttribute(PersonalizationScope.Shared)]
[LocalizedWebDisplayNameAttribute("SubmitOrderWebDisplayNameOrderConfirmation")]
public string OrderConfirmationPage { get; set; }
```

``` c++
[LocalizedCategoryAttribute(L"Order Settings")]
[WebBrowsableAttribute(true)]
[LocalizedWebDescriptionAttribute(L"SubmitOrderWebDescriptionOrderConfirmation")]
[WebPartStorageAttribute(Storage::Shared)]
[PersonalizableAttribute(PersonalizationScope::Shared)]
[LocalizedWebDisplayNameAttribute(L"SubmitOrderWebDisplayNameOrderConfirmation")]
public:
property String^ OrderConfirmationPage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SubmitOrder Class](submitorder-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

