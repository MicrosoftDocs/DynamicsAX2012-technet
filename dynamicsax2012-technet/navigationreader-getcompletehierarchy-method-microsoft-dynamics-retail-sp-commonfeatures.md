---
title: NavigationReader.GetCompleteHierarchy Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetCompleteHierarchy Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.GetCompleteHierarchy(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationreader.getcompletehierarchy(v=AX.60)
ms:contentKeyID: 62205251
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.GetCompleteHierarchy
dev_langs:
- CSharp
- C++
- VB
---

# GetCompleteHierarchy Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets complete hierarchy of navigation menu.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCompleteHierarchy ( _
    includeStaticCategories As Boolean _
) As IList(Of NavigationalCategory)
'Usage
Dim includeStaticCategories As Boolean
Dim returnValue As IList(Of NavigationalCategory)

returnValue = NavigationReader.GetCompleteHierarchy(includeStaticCategories)
```

``` csharp
public static IList<NavigationalCategory> GetCompleteHierarchy(
    bool includeStaticCategories
)
```

``` c++
public:
static IList<NavigationalCategory^>^ GetCompleteHierarchy(
    bool includeStaticCategories
)
```

#### Parameters

  - includeStaticCategories  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)\>  
List of categories which represent complete navigational hierarchy with all its children.  

## See Also

#### Reference

[NavigationReader Class](navigationreader-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

