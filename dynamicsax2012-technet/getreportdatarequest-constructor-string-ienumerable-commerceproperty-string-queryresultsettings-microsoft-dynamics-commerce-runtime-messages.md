---
title: GetReportDataRequest Constructor (String, IEnumerable(CommerceProperty), String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReportDataRequest Constructor (String, IEnumerable(CommerceProperty), String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataRequest.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty},System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getreportdatarequest.getreportdatarequest(v=AX.60)
ms:contentKeyID: 65321921
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReportDataRequest Constructor (String, IEnumerable(CommerceProperty), String, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reportId As String, _
    reportParameters As IEnumerable(Of CommerceProperty), _
    locale As String, _
    settings As QueryResultSettings _
)
'Usage
Dim reportId As String
Dim reportParameters As IEnumerable(Of CommerceProperty)
Dim locale As String
Dim settings As QueryResultSettings

Dim instance As New GetReportDataRequest(reportId, _
    reportParameters, locale, settings)
```

``` csharp
public GetReportDataRequest(
    string reportId,
    IEnumerable<CommerceProperty> reportParameters,
    string locale,
    QueryResultSettings settings
)
```

``` c++
public:
GetReportDataRequest(
    String^ reportId, 
    IEnumerable<CommerceProperty^>^ reportParameters, 
    String^ locale, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reportParameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetReportDataRequest Class](getreportdatarequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReportDataRequest Overload](getreportdatarequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

