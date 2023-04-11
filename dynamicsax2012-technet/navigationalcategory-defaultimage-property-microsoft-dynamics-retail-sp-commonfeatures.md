---
title: NavigationalCategory.DefaultImage Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: DefaultImage Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.DefaultImage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.defaultimage(v=AX.60)
ms:contentKeyID: 62204022
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.DefaultImage
dev_langs:
- CSharp
- C++
- VB
---

# DefaultImage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default image.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property DefaultImage As String
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As String

value = instance.DefaultImage
```

``` csharp
public string DefaultImage { get; private set; }
```

``` c++
public:
property String^ DefaultImage {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The default image.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

