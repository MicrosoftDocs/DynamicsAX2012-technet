---
title: NavigationalCategory.Children Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Children Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Children
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.children(v=AX.60)
ms:contentKeyID: 62203006
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Children
dev_langs:
- CSharp
- C++
- VB
---

# Children Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the children.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property Children As IList(Of NavigationalCategory)
    Get
    Set
'Usage
Dim instance As NavigationalCategory
Dim value As IList(Of NavigationalCategory)

value = instance.Children

instance.Children = value
```

``` csharp
public IList<NavigationalCategory> Children { get; set; }
```

``` c++
public:
property IList<NavigationalCategory^>^ Children {
    IList<NavigationalCategory^>^ get ();
    void set (IList<NavigationalCategory^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[NavigationalCategory](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)\>  
The children.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

