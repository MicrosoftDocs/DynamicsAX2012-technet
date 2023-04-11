---
title: NavigationalCategory.IsStatic Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: IsStatic Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.IsStatic
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.isstatic(v=AX.60)
ms:contentKeyID: 62207395
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.IsStatic
dev_langs:
- CSharp
- C++
- VB
---

# IsStatic Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this instance is static.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property IsStatic As Boolean
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As Boolean

value = instance.IsStatic
```

``` csharp
public bool IsStatic { get; private set; }
```

``` c++
public:
property bool IsStatic {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if this instance is static; otherwise, false.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

