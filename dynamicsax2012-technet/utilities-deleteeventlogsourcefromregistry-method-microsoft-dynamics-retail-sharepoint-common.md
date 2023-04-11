---
title: Utilities.DeleteEventLogSourceFromRegistry Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: DeleteEventLogSourceFromRegistry Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.DeleteEventLogSourceFromRegistry(System.Collections.Generic.IEnumerable{System.String},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.utilities.deleteeventlogsourcefromregistry(v=AX.60)
ms:contentKeyID: 62203882
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.Utilities.DeleteEventLogSourceFromRegistry
dev_langs:
- CSharp
- C++
- VB
---

# DeleteEventLogSourceFromRegistry Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Removes the registry key needed for an event log source on a list of windows computers.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub DeleteEventLogSourceFromRegistry ( _
    serverAddresses As IEnumerable(Of String), _
    eventLogSourceName As String _
)
'Usage
Dim serverAddresses As IEnumerable(Of String)
Dim eventLogSourceName As String

Utilities.DeleteEventLogSourceFromRegistry(serverAddresses, _
    eventLogSourceName)
```

``` csharp
public static void DeleteEventLogSourceFromRegistry(
    IEnumerable<string> serverAddresses,
    string eventLogSourceName
)
```

``` c++
public:
static void DeleteEventLogSourceFromRegistry(
    IEnumerable<String^>^ serverAddresses, 
    String^ eventLogSourceName
)
```

#### Parameters

  - serverAddresses  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - eventLogSourceName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Utilities Class](utilities-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

