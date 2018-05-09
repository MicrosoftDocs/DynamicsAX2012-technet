---
title: NavigationReader.GetChildren Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: GetChildren Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.GetChildren(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.navigationreader.getchildren(v=AX.60)
ms:contentKeyID: 62207143
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationReader.GetChildren
dev_langs:
- CSharp
- C++
- VB
---

# GetChildren Method

By given category ID returns its complete children hierarchy.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetChildren ( _
    parentCategoryId As Guid _
) As IList(Of NavigationalCategory)
'Usage
Dim parentCategoryId As Guid
Dim returnValue As IList(Of NavigationalCategory)

returnValue = NavigationReader.GetChildren(parentCategoryId)
```

``` csharp
public static IList<NavigationalCategory> GetChildren(
    Guid parentCategoryId
)
```

``` c++
public:
static IList<NavigationalCategory^>^ GetChildren(
    Guid parentCategoryId
)
```

#### Parameters

  - parentCategoryId  
    Type: [System.Guid](https://technet.microsoft.com/en-us/library/cey1zx63\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)\>  
Returns children hierarchy for the parent term.  

## See Also

#### Reference

[NavigationReader Class](navigationreader-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

