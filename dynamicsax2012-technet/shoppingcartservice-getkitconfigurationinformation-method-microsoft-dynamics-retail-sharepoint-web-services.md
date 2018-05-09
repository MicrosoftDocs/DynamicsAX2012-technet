---
title: ShoppingCartService.GetKitConfigurationInformation Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetKitConfigurationInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetKitConfigurationInformation(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice.getkitconfigurationinformation(v=AX.60)
ms:contentKeyID: 62205223
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService.GetKitConfigurationInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetKitConfigurationInformation Method

Gets information about the specific kit configuration that has the provided kit line values.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function GetKitConfigurationInformation ( _
    kitProductMasterIdentifier As Long, _
    catalogId As Long, _
    kitLines As IEnumerable(Of KitLine) _
) As KitConfigurationResponse
'Usage
Dim instance As ShoppingCartService
Dim kitProductMasterIdentifier As Long
Dim catalogId As Long
Dim kitLines As IEnumerable(Of KitLine)
Dim returnValue As KitConfigurationResponse

returnValue = instance.GetKitConfigurationInformation(kitProductMasterIdentifier, _
    catalogId, kitLines)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public KitConfigurationResponse GetKitConfigurationInformation(
    long kitProductMasterIdentifier,
    long catalogId,
    IEnumerable<KitLine> kitLines
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual KitConfigurationResponse^ GetKitConfigurationInformation(
    long long kitProductMasterIdentifier, 
    long long catalogId, 
    IEnumerable<KitLine^>^ kitLines
) sealed
```

#### Parameters

  - kitProductMasterIdentifier  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[KitLine](kitline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationResponse](kitconfigurationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Specific kit configuration information.  

#### Implements

[IShoppingCartService.GetKitConfigurationInformation(Int64, Int64, IEnumerable\<KitLine\>)](ishoppingcartservice-getkitconfigurationinformation-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

