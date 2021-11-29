---
title: DemoService.GenerateServerError Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GenerateServerError Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService.GenerateServerError
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.demoservice.generateservererror(v=AX.60)
ms:contentKeyID: 62206768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.DemoService.GenerateServerError
dev_langs:
- CSharp
- C++
- VB
---

# GenerateServerError Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Generates the server error.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Sub GenerateServerError
'Usage
Dim instance As DemoService

instance.GenerateServerError()
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public void GenerateServerError()
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual void GenerateServerError() sealed
```

#### Implements

[IDemoService.GenerateServerError()](idemoservice-generateservererror-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/6byb74h9(v=ax.60)">NotImplementedException</a></td>
<td><p>Always thrown.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[DemoService Class](demoservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

