---
title: LoggingService Class (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: LoggingService Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.loggingservice(v=AX.60)
ms:contentKeyID: 62203849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService
dev_langs:
- CSharp
- C++
- VB
---

# LoggingService Class

Logging service for sharepoint code. This enables us to configured the trace levels and severity levels for throttling in the CA app.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("D64DEDE4-3D1D-42CC-AF40-DB09F0DFA309")> _
Public Class LoggingService _
    Inherits SPDiagnosticsServiceBase
'Usage
Dim instance As LoggingService
```

``` csharp
[GuidAttribute("D64DEDE4-3D1D-42CC-AF40-DB09F0DFA309")]
public class LoggingService : SPDiagnosticsServiceBase
```

``` c++
[GuidAttribute(L"D64DEDE4-3D1D-42CC-AF40-DB09F0DFA309")]
public ref class LoggingService : public SPDiagnosticsServiceBase
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPPersistedUpgradableObject  
        SPService  
          SPDiagnosticsServiceBase  
            Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

