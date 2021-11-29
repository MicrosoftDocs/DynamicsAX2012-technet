---
title: NavigationReader.SplitCategories Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SplitCategories Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.SplitCategories(System.Collections.Generic.IList{Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationreader.splitcategories(v=AX.60)
ms:contentKeyID: 62207016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.SplitCategories
dev_langs:
- CSharp
- C++
- VB
---

# SplitCategories Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Splits categories by columns.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function SplitCategories ( _
    rawCategories As IList(Of NavigationalCategory) _
) As IOrderedEnumerable(Of KeyValuePair(Of Integer, List(Of NavigationalCategory)))
'Usage
Dim rawCategories As IList(Of NavigationalCategory)
Dim returnValue As IOrderedEnumerable(Of KeyValuePair(Of Integer, List(Of NavigationalCategory)))

returnValue = NavigationReader.SplitCategories(rawCategories)
```

``` csharp
public static IOrderedEnumerable<KeyValuePair<int, List<NavigationalCategory>>> SplitCategories(
    IList<NavigationalCategory> rawCategories
)
```

``` c++
public:
static IOrderedEnumerable<KeyValuePair<int, List<NavigationalCategory^>^>>^ SplitCategories(
    IList<NavigationalCategory^>^ rawCategories
)
```

#### Parameters

  - rawCategories  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)\>  

#### Return Value

Type: [System.Linq.IOrderedEnumerable](https://technet.microsoft.com/library/bb534852\(v=ax.60\))\<[KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)), [List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)\>\>\>  
Categories split by columns.  

## See Also

#### Reference

[NavigationReader Class](navigationreader-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

