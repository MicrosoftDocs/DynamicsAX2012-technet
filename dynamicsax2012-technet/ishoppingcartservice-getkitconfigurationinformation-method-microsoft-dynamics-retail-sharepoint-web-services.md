---
title: IShoppingCartService.GetKitConfigurationInformation Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetKitConfigurationInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetKitConfigurationInformation(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.getkitconfigurationinformation(v=AX.60)
ms:contentKeyID: 62204616
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.GetKitConfigurationInformation
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
<OperationContractAttribute> _
Function GetKitConfigurationInformation ( _
    kitProductMasterIdentifier As Long, _
    catalogId As Long, _
    kitLines As IEnumerable(Of KitLine) _
) As KitConfigurationResponse
'Usage
Dim instance As IShoppingCartService
Dim kitProductMasterIdentifier As Long
Dim catalogId As Long
Dim kitLines As IEnumerable(Of KitLine)
Dim returnValue As KitConfigurationResponse

returnValue = instance.GetKitConfigurationInformation(kitProductMasterIdentifier, _
    catalogId, kitLines)
```

``` csharp
[OperationContractAttribute]
KitConfigurationResponse GetKitConfigurationInformation(
    long kitProductMasterIdentifier,
    long catalogId,
    IEnumerable<KitLine> kitLines
)
```

``` c++
[OperationContractAttribute]
KitConfigurationResponse^ GetKitConfigurationInformation(
    long long kitProductMasterIdentifier, 
    long long catalogId, 
    IEnumerable<KitLine^>^ kitLines
)
```

#### Parameters

  - kitProductMasterIdentifier  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[KitLine](kitline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationResponse](kitconfigurationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Specific kit configuration information.  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

