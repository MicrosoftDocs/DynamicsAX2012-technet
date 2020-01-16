---
title: GetOLTPReportDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetOLTPReportDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOLTPReportDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getoltpreportdatarequest.getoltpreportdatarequest(v=AX.60)
ms:contentKeyID: 65317802
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOLTPReportDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetOLTPReportDataRequest Constructor

Initializes a new instance of the [GetOLTPReportDataRequest](getoltpreportdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    config As ReportConfiguration, _
    locale As String, _
    settings As QueryResultSettings _
)
'Usage
Dim config As ReportConfiguration
Dim locale As String
Dim settings As QueryResultSettings

Dim instance As New GetOLTPReportDataRequest(config, _
    locale, settings)
```

``` csharp
public GetOLTPReportDataRequest(
    ReportConfiguration config,
    string locale,
    QueryResultSettings settings
)
```

``` c++
public:
GetOLTPReportDataRequest(
    ReportConfiguration^ config, 
    String^ locale, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - config  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetOLTPReportDataRequest Class](getoltpreportdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

