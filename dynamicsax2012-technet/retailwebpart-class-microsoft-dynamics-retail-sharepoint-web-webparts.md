---
title: RetailWebPart Class (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts)
TOCTitle: RetailWebPart Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.RetailWebPart
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.retailwebpart(v=AX.60)
ms:contentKeyID: 62206830
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.RetailWebPart
dev_langs:
- CSharp
- C++
- VB
---

# RetailWebPart Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Base class for providing shared functionality across all retail web parts.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public MustInherit Class RetailWebPart _
    Inherits WebPart
'Usage
Dim instance As RetailWebPart
```

``` csharp
[ComVisibleAttribute(false)]
public abstract class RetailWebPart : WebPart
```

``` c++
[ComVisibleAttribute(false)]
public ref class RetailWebPart abstract : public WebPart
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Web.UI.Control](https://technet.microsoft.com/library/983zwx2h\(v=ax.60\))  
    [System.Web.UI.WebControls.WebControl](https://technet.microsoft.com/library/k1x24e42\(v=ax.60\))  
      [System.Web.UI.WebControls.Panel](https://technet.microsoft.com/library/x25wh2hz\(v=ax.60\))  
        [System.Web.UI.WebControls.WebParts.Part](https://technet.microsoft.com/library/yb25w952\(v=ax.60\))  
          [System.Web.UI.WebControls.WebParts.WebPart](https://technet.microsoft.com/library/h0t1fxe7\(v=ax.60\))  
            Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.RetailWebPart  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Address](address-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddressDisplay](addressdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.AddToCart](addtocart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Authentication](authentication-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Checkout](checkout-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Customer](customer-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.CustomerDisplay](customerdisplay-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.MiniShoppingCart](minishoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.PromotionCode](promotioncode-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.StoreProductAvailability](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  
              [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.SubmitOrder](submitorder-class-microsoft-dynamics-retail-sharepoint-web-webparts.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-namespace.md)

