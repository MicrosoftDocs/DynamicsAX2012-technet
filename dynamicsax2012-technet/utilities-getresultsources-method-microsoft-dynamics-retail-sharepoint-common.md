---
title: Utilities.GetResultSources Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: GetResultSources Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetResultSources
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.utilities.getresultsources(v=AX.60)
ms:contentKeyID: 62203875
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.GetResultSources
dev_langs:
- CSharp
- C++
- VB
---

# GetResultSources Method

Returns an enumerator with the result Sources

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetResultSources As IEnumerable(Of Source)
'Usage
Dim returnValue As IEnumerable(Of Source)

returnValue = Utilities.GetResultSources()
```

``` csharp
public static IEnumerable<Source> GetResultSources()
```

``` c++
public:
static IEnumerable<Source^>^ GetResultSources()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<Source\>  
Returns an enumerator with the Sources or empty enumerator if there are no Result Sources  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

