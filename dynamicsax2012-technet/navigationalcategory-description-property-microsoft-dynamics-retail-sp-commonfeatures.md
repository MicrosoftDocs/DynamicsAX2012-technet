---
title: NavigationalCategory.Description Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.navigationalcategory.description(v=AX.60)
ms:contentKeyID: 62205655
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.NavigationalCategory.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the description.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Property Description As String
    Get
    Private Set
'Usage
Dim instance As NavigationalCategory
Dim value As String

value = instance.Description
```

``` csharp
public string Description { get; private set; }
```

``` c++
public:
property String^ Description {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description.  

## See Also

#### Reference

[NavigationalCategory Class](navigationalcategory-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

