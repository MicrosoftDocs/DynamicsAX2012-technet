---
title: LoggingService.WriteEvent Method (String, String, , UInt16, String, Object ) (Microsoft.Dynamics.Retail.SharePoint.Common)
TOCTitle: WriteEvent Method (String, String, , UInt16, String, Object )
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Common.LoggingService.WriteEvent(System.String,System.String,Microsoft.SharePoint.Administration.EventSeverity,System.UInt16,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.common.loggingservice.writeevent(v=AX.60)
ms:contentKeyID: 62204039
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# WriteEvent Method (String, String, , UInt16, String, Object )[AX 2012]

Writes an event to the event log

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Common](microsoft-dynamics-retail-sharepoint-common-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub WriteEvent ( _
    loggingServiceName As String, _
    categoryName As String, _
    eventSeverity As EventSeverity, _
    id As UShort, _
    format As String, _
    ParamArray arg As Object() _
)
'Usage
Dim loggingServiceName As String
Dim categoryName As String
Dim eventSeverity As EventSeverity
Dim id As UShort
Dim format As String
Dim arg As Object()

LoggingService.WriteEvent(loggingServiceName, _
    categoryName, eventSeverity, id, _
    format, arg)
```

``` csharp
public static void WriteEvent(
    string loggingServiceName,
    string categoryName,
    EventSeverity eventSeverity,
    ushort id,
    string format,
    params Object[] arg
)
```

``` c++
public:
static void WriteEvent(
    String^ loggingServiceName, 
    String^ categoryName, 
    EventSeverity eventSeverity, 
    unsigned short id, 
    String^ format, 
    ... array<Object^>^ arg
)
```

#### Parameters

  - loggingServiceName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - categoryName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - eventSeverity  
    Type: EventSeverity  

<!-- end list -->

  - id  
    Type: [System.UInt16](https://technet.microsoft.com/en-us/library/s6eyk10z\(v=ax.60\))  

<!-- end list -->

  - format  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - arg  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[LoggingService Class](loggingservice-class-microsoft-dynamics-retail-sharepoint-common.md)

[WriteEvent Overload](loggingservice-writeevent-method-microsoft-dynamics-retail-sharepoint-common.md)

[Microsoft.Dynamics.Retail.SharePoint.Common Namespace](microsoft-dynamics-retail-sharepoint-common-namespace.md)

