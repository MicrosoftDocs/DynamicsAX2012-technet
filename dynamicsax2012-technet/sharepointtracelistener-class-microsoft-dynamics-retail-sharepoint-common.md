---
title: SharePointTraceListener Class (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: SharePointTraceListener Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtracelistener(v=AX.60)
ms:contentKeyID: 62207490
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener
dev_langs:
- CSharp
- C++
- VB
---

# SharePointTraceListener Class

Directs tracing to a specific class that writes to the Sharepoint ULS (Unified Logging System).

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
Public Class SharePointTraceListener _
    Inherits TraceListener
'Usage
Dim instance As SharePointTraceListener
```

``` csharp
[ComVisibleAttribute(false)]
public class SharePointTraceListener : TraceListener
```

``` c++
[ComVisibleAttribute(false)]
public ref class SharePointTraceListener : public TraceListener
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.MarshalByRefObject](https://technet.microsoft.com/library/w4302s1f\(v=ax.60\))  
    [System.Diagnostics.TraceListener](https://technet.microsoft.com/library/hy72797k\(v=ax.60\))  
      Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

