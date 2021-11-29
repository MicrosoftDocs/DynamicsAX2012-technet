---
title: SalesOrderItem.CalculatedAmount Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CalculatedAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.CalculatedAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorderitem.calculatedamount(v=AX.60)
ms:contentKeyID: 62205469
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.CalculatedAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculatedAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the computed charge amount.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CalculatedAmount As Decimal
    Get
    Set
'Usage
Dim instance As SalesOrderItem
Dim value As Decimal

value = instance.CalculatedAmount

instance.CalculatedAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal CalculatedAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal CalculatedAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

This amount is the actual computed amount for the charge line. It does not necessary map to the configuration.

## See Also

#### Reference

[SalesOrderItem Class](salesorderitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

