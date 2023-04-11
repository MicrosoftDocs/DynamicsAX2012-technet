---
title: NavigationalCategory.SortIndex Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SortIndex Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.SortIndex
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.sortindex(v=AX.60)
ms:contentKeyID: 62203876
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.SortIndex
dev_langs:
- CSharp
- C++
- VB
---

# SortIndex Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the index of the sort.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property SortIndex As Integer
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As Integer

value = instance.SortIndex
```

``` csharp
public int SortIndex { get; private set; }
```

``` c++
public:
property int SortIndex {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The index of the sort.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

