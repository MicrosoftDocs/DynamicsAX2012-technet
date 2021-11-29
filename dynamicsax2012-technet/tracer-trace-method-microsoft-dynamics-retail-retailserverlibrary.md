---
title: Tracer.Trace Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: Trace Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.Tracer.Trace(System.Net.Http.HttpRequestMessage,System.String,System.Web.Http.Tracing.TraceLevel,System.Action{System.Web.Http.Tracing.TraceRecord})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.tracer.trace(v=AX.60)
ms:contentKeyID: 62202151
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.Tracer.Trace
dev_langs:
- CSharp
- C++
- VB
---

# Trace Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The trace method.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Sub Trace ( _
    request As HttpRequestMessage, _
    category As String, _
    level As TraceLevel, _
    traceAction As Action(Of TraceRecord) _
)
'Usage
Dim instance As Tracer
Dim request As HttpRequestMessage
Dim category As String
Dim level As TraceLevel
Dim traceAction As Action(Of TraceRecord)

instance.Trace(request, category, level, _
    traceAction)
```

``` csharp
public void Trace(
    HttpRequestMessage request,
    string category,
    TraceLevel level,
    Action<TraceRecord> traceAction
)
```

``` c++
public:
virtual void Trace(
    HttpRequestMessage^ request, 
    String^ category, 
    TraceLevel level, 
    Action<TraceRecord^>^ traceAction
) sealed
```

#### Parameters

  - request  
    Type: HttpRequestMessage  

<!-- end list -->

  - category  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - level  
    Type: TraceLevel  

<!-- end list -->

  - traceAction  
    Type: [System.Action](https://technet.microsoft.com/library/018hxwa8\(v=ax.60\))\<TraceRecord\>  

#### Implements

ITraceWriterTrace(HttpRequestMessage, String, TraceLevel, Action\<TraceRecord\>)  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Exception will be thrown if incoming arguments are invalid.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Tracer Class](tracer-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

