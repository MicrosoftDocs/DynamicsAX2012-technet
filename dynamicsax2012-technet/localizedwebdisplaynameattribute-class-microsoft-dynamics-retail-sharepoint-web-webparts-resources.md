---
title: LocalizedWebDisplayNameAttribute Class (Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources)
TOCTitle: LocalizedWebDisplayNameAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDisplayNameAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.webparts.resources.localizedwebdisplaynameattribute(v=AX.60)
ms:contentKeyID: 62206230
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDisplayNameAttribute
dev_langs:
- CSharp
- C++
- VB
---

# LocalizedWebDisplayNameAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Provides localizability support for WebDisplayNameAttribute.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.WebParts (in Microsoft.Dynamics.Retail.SP.Web.WebParts.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property)> _
Public NotInheritable Class LocalizedWebDisplayNameAttribute _
    Inherits WebDisplayNameAttribute
'Usage
Dim instance As LocalizedWebDisplayNameAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property)]
public sealed class LocalizedWebDisplayNameAttribute : WebDisplayNameAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property)]
public ref class LocalizedWebDisplayNameAttribute sealed : public WebDisplayNameAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    [System.Web.UI.WebControls.WebParts.WebDisplayNameAttribute](https://technet.microsoft.com/library/ms157335\(v=ax.60\))  
      Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources.LocalizedWebDisplayNameAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.WebParts.Resources Namespace](microsoft-dynamics-retail-sharepoint-web-webparts-resources-namespace.md)

