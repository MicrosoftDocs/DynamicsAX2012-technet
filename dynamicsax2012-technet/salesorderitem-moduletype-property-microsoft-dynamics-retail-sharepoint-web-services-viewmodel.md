---
title: SalesOrderItem.ModuleType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ModuleType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.ModuleType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorderitem.moduletype(v=AX.60)
ms:contentKeyID: 62203573
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.ModuleType
dev_langs:
- CSharp
- C++
- VB
---

# ModuleType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets which module the charge comes from.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ModuleType As String
    Get
    Set
'Usage
Dim instance As SalesOrderItem
Dim value As String

value = instance.ModuleType

instance.ModuleType = value
```

``` csharp
[DataMemberAttribute]
public string ModuleType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ModuleType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Indicates whether this is a customer or delivery charge.

## See Also

#### Reference

[SalesOrderItem Class](salesorderitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

