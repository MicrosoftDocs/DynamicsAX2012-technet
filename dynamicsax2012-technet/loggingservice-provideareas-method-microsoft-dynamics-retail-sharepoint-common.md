---
title: LoggingService.ProvideAreas Method  (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: ProvideAreas Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.ProvideAreas
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.loggingservice.provideareas(v=AX.60)
ms:contentKeyID: 62204240
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.ProvideAreas
dev_langs:
- CSharp
- C++
- VB
---

# ProvideAreas Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns a collection of the event and trace logging categories used with this service.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function ProvideAreas As IEnumerable(Of SPDiagnosticsArea)
'Usage
Dim returnValue As IEnumerable(Of SPDiagnosticsArea)

returnValue = Me.ProvideAreas()
```

``` csharp
protected override IEnumerable<SPDiagnosticsArea> ProvideAreas()
```

``` c++
protected:
virtual IEnumerable<SPDiagnosticsArea^>^ ProvideAreas() override
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<SPDiagnosticsArea\>  
The diagnostic areas registered for the logging service.  

## See Also

#### Reference

[LoggingService Class](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

