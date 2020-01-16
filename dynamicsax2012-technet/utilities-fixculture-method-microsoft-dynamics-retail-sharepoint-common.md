---
title: Utilities.FixCulture Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: FixCulture Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.FixCulture(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.fixculture(v=AX.60)
ms:contentKeyID: 62206816
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.FixCulture
dev_langs:
- CSharp
- C++
- VB
---

# FixCulture Method

Fixes country only cultures by adding a region part which matches the country.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function FixCulture ( _
    cultureName As String _
) As String
'Usage
Dim cultureName As String
Dim returnValue As String

returnValue = Utilities.FixCulture(cultureName)
```

``` csharp
public static string FixCulture(
    string cultureName
)
```

``` c++
public:
static String^ FixCulture(
    String^ cultureName
)
```

#### Parameters

  - cultureName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Fixed culture name.  

## Remarks

This is function converts cultures which have just country info to the cultures which also have region info by duplicating country info in the region. This is short term fix for the SharePoint issue which supports (while rendering terms' labels) only such locales like fr-FR, it-IT but if we have a translation for just fr or it or ru - it will not be understood by SharePoint because it is only capable of recognizing such full name locales as fr-FR, it-IT, ru-RU and so on, in fact it only recognizes those locales which can be found in an appropriate language packs and there are no languages packs let's say for fr or fr-BE or ru.

So, when this function gets culture fr it will return fr-FR, but in case it will include the region - it will not be touched. SharePoint team has been notified and we are working together on possible long term solution.

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

