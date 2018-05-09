---
title: GetReportConfigurationDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetReportConfigurationDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReportConfigurationDataRequest.#ctor(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreportconfigurationdatarequest.getreportconfigurationdatarequest(v=AX.60)
ms:contentKeyID: 65321630
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReportConfigurationDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetReportConfigurationDataRequest Constructor

Initializes a new instance of the [GetReportConfigurationDataRequest](getreportconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reportId As String, _
    locale As String, _
    settings As QueryResultSettings _
)
'Usage
Dim reportId As String
Dim locale As String
Dim settings As QueryResultSettings

Dim instance As New GetReportConfigurationDataRequest(reportId, _
    locale, settings)
```

``` csharp
public GetReportConfigurationDataRequest(
    string reportId,
    string locale,
    QueryResultSettings settings
)
```

``` c++
public:
GetReportConfigurationDataRequest(
    String^ reportId, 
    String^ locale, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetReportConfigurationDataRequest Class](getreportconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

