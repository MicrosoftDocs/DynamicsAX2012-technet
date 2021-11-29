---
title: CheckoutService.CreateOrder Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.CreateOrder(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.checkoutservice.createorder(v=AX.60)
ms:contentKeyID: 62205289
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.CheckoutService.CreateOrder
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Processes a sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function CreateOrder ( _
    tenderDataLine As Collection(Of TenderDataLine), _
    emailAddress As String _
) As CreateSalesOrderResponse
'Usage
Dim instance As CheckoutService
Dim tenderDataLine As Collection(Of TenderDataLine)
Dim emailAddress As String
Dim returnValue As CreateSalesOrderResponse

returnValue = instance.CreateOrder(tenderDataLine, _
    emailAddress)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public CreateSalesOrderResponse CreateOrder(
    Collection<TenderDataLine> tenderDataLine,
    string emailAddress
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual CreateSalesOrderResponse^ CreateOrder(
    Collection<TenderDataLine^>^ tenderDataLine, 
    String^ emailAddress
) sealed
```

#### Parameters

  - tenderDataLine  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

<!-- end list -->

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CreateSalesOrderResponse](createsalesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The updated shopping cart item collection.  

#### Implements

[ICheckoutService.CreateOrder(Collection\<TenderDataLine\>, String)](icheckoutservice-createorder-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[CheckoutService Class](checkoutservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

