---
title: SharePointTraceListener.TraceEvent Method (TraceEventCache, String, TraceEventType, Int32, String, Object ) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: TraceEvent Method (TraceEventCache, String, TraceEventType, Int32, String, Object )
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.SharePointTraceListener.TraceEvent(System.Diagnostics.TraceEventCache,System.String,System.Diagnostics.TraceEventType,System.Int32,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.common.sharepointtracelistener.traceevent(v=AX.60)
ms:contentKeyID: 62207024
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# TraceEvent Method (TraceEventCache, String, TraceEventType, Int32, String, Object[])


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Writes trace information, a message, and event information to the listener specific output.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub TraceEvent ( _
    eventCache As TraceEventCache, _
    source As String, _
    eventType As TraceEventType, _
    id As Integer, _
    format As String, _
    ParamArray args As Object() _
)
'Usage
Dim instance As SharePointTraceListener
Dim eventCache As TraceEventCache
Dim source As String
Dim eventType As TraceEventType
Dim id As Integer
Dim format As String
Dim args As Object()

instance.TraceEvent(eventCache, source, _
    eventType, id, format, args)
```

``` csharp
public override void TraceEvent(
    TraceEventCache eventCache,
    string source,
    TraceEventType eventType,
    int id,
    string format,
    params Object[] args
)
```

``` c++
public:
virtual void TraceEvent(
    TraceEventCache^ eventCache, 
    String^ source, 
    TraceEventType eventType, 
    int id, 
    String^ format, 
    ... array<Object^>^ args
) override
```

#### Parameters

  - eventCache  
    Type: [System.Diagnostics.TraceEventCache](https://technet.microsoft.com/library/9369bzbf\(v=ax.60\))  

<!-- end list -->

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - eventType  
    Type: [System.Diagnostics.TraceEventType](https://technet.microsoft.com/library/5t134hfw\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - format  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[SharePointTraceListener Class](sharepointtracelistener-class-microsoft-dynamics-retail-sharepoint-common.md)

[TraceEvent Overload](sharepointtracelistener-traceevent-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

