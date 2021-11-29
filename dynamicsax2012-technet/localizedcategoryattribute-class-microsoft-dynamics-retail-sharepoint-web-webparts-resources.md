---
title: LocalizedCategoryAttribute Class (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources)
TOCTitle: LocalizedCategoryAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedCategoryAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resources.localizedcategoryattribute(v=AX.60)
ms:contentKeyID: 62203851
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedCategoryAttribute
dev_langs:
- CSharp
- C++
- VB
---

# LocalizedCategoryAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Provides localizability support for CategoryAttribute.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property)> _
Public NotInheritable Class LocalizedCategoryAttribute _
    Inherits CategoryAttribute
'Usage
Dim instance As LocalizedCategoryAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property)]
public sealed class LocalizedCategoryAttribute : CategoryAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property)]
public ref class LocalizedCategoryAttribute sealed : public CategoryAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    [System.ComponentModel.CategoryAttribute](https://technet.microsoft.com/library/w0ee2hf1\(v=ax.60\))  
      Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedCategoryAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)

