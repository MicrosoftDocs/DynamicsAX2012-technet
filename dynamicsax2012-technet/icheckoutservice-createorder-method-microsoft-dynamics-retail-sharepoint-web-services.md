---
title: ICheckoutService.CreateOrder Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.CreateOrder(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.icheckoutservice.createorder(v=AX.60)
ms:contentKeyID: 62203202
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ICheckoutService.CreateOrder
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrder Method

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function CreateOrder ( _
    tenderDataLine As Collection(Of TenderDataLine), _
    emailAddress As String _
) As CreateSalesOrderResponse
'Usage
Dim instance As ICheckoutService
Dim tenderDataLine As Collection(Of TenderDataLine)
Dim emailAddress As String
Dim returnValue As CreateSalesOrderResponse

returnValue = instance.CreateOrder(tenderDataLine, _
    emailAddress)
```

``` csharp
[OperationContractAttribute]
CreateSalesOrderResponse CreateOrder(
    Collection<TenderDataLine> tenderDataLine,
    string emailAddress
)
```

``` c++
[OperationContractAttribute]
CreateSalesOrderResponse^ CreateOrder(
    Collection<TenderDataLine^>^ tenderDataLine, 
    String^ emailAddress
)
```

#### Parameters

  - tenderDataLine  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

<!-- end list -->

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CreateSalesOrderResponse](createsalesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

