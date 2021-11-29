---
title: StoreProductAvailabilityItem.WarehouseInventoryDimensionId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: WarehouseInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityItem.WarehouseInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeproductavailabilityitem.warehouseinventorydimensionid(v=AX.60)
ms:contentKeyID: 62202732
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityItem.WarehouseInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseInventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the warehouse inventory dimension ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WarehouseInventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As StoreProductAvailabilityItem
Dim value As String

value = instance.WarehouseInventoryDimensionId

instance.WarehouseInventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
public string WarehouseInventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ WarehouseInventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The warehouse inventory dimension ID.  

## See Also

#### Reference

[StoreProductAvailabilityItem Class](storeproductavailabilityitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

