---
title: CreateSalesOrderResponse.OrderNumber Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: OrderNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CreateSalesOrderResponse.OrderNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.createsalesorderresponse.ordernumber(v=AX.60)
ms:contentKeyID: 62205340
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CreateSalesOrderResponse.OrderNumber
dev_langs:
- CSharp
- C++
- VB
---

# OrderNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales order number.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderNumber As String
    Get
    Set
'Usage
Dim instance As CreateSalesOrderResponse
Dim value As String

value = instance.OrderNumber

instance.OrderNumber = value
```

``` csharp
[DataMemberAttribute]
public string OrderNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OrderNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CreateSalesOrderResponse Class](createsalesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

