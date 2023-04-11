---
title: NavigationalCategory.ColumnIndex Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: ColumnIndex Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.ColumnIndex
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.columnindex(v=AX.60)
ms:contentKeyID: 62204908
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.ColumnIndex
dev_langs:
- CSharp
- C++
- VB
---

# ColumnIndex Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the index of the column.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnIndex As Integer
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As Integer

value = instance.ColumnIndex
```

``` csharp
public int ColumnIndex { get; private set; }
```

``` c++
public:
property int ColumnIndex {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The index of the column.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

