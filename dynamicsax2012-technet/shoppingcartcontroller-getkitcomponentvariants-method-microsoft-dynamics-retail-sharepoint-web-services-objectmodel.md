---
title: ShoppingCartController.GetKitComponentVariants Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetKitComponentVariants Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartController.GetKitComponentVariants(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.shoppingcartcontroller.getkitcomponentvariants(v=AX.60)
ms:contentKeyID: 62207537
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartController.GetKitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetKitComponentVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the applicable variants of a kit component.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetKitComponentVariants ( _
    kitComponentProductId As Long, _
    kitComponentParentId As Long, _
    parentKitId As Long, _
    kitComponentLineId As Long, _
    catalogId As Long _
) As IEnumerable(Of StorefrontListItem)
'Usage
Dim kitComponentProductId As Long
Dim kitComponentParentId As Long
Dim parentKitId As Long
Dim kitComponentLineId As Long
Dim catalogId As Long
Dim returnValue As IEnumerable(Of StorefrontListItem)

returnValue = ShoppingCartController.GetKitComponentVariants(kitComponentProductId, _
    kitComponentParentId, parentKitId, _
    kitComponentLineId, catalogId)
```

``` csharp
public static IEnumerable<StorefrontListItem> GetKitComponentVariants(
    long kitComponentProductId,
    long kitComponentParentId,
    long parentKitId,
    long kitComponentLineId,
    long catalogId
)
```

``` c++
public:
static IEnumerable<StorefrontListItem^>^ GetKitComponentVariants(
    long long kitComponentProductId, 
    long long kitComponentParentId, 
    long long parentKitId, 
    long long kitComponentLineId, 
    long long catalogId
)
```

#### Parameters

  - kitComponentProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentParentId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentKitId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentLineId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StorefrontListItem](storefrontlistitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns a collection of kit component variants.  

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
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>kitComponentProductId or kitComponentParentId or parentKitId or kitComponentLineId or catalogId</p></td>
</tr>
<tr class="even">
<td><a href="https://technet.microsoft.com/library/2asft85a(v=ax.60)">InvalidOperationException</a></td>
<td><p>No products are found for the given criteria.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

