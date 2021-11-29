---
title: ServiceResponse.Errors Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Errors Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse.Errors
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.serviceresponse.errors(v=AX.60)
ms:contentKeyID: 62204817
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ServiceResponse.Errors
dev_langs:
- CSharp
- C++
- VB
---

# Errors Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of the [ResponseError](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Errors As List(Of ResponseError)
    Get
    Private Set
'Usage
Dim instance As ServiceResponse
Dim value As List(Of ResponseError)

value = instance.Errors
```

``` csharp
[DataMemberAttribute]
public List<ResponseError> Errors { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property List<ResponseError^>^ Errors {
    List<ResponseError^>^ get ();
    private: void set (List<ResponseError^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[ResponseError](responseerror-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [List\<T\>](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\)).  

## See Also

#### Reference

[ServiceResponse Class](serviceresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

