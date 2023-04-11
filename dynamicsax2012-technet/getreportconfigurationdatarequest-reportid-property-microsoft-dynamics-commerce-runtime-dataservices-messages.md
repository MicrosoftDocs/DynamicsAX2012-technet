---
title: GetReportConfigurationDataRequest.ReportId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReportId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReportConfigurationDataRequest.ReportId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getreportconfigurationdatarequest.reportid(v=AX.60)
ms:contentKeyID: 65320065
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetReportConfigurationDataRequest.ReportId
dev_langs:
- CSharp
- C++
- VB
---

# ReportId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the id of the report.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportId As String
    Get
    Private Set
'Usage
Dim instance As GetReportConfigurationDataRequest
Dim value As String

value = instance.ReportId
```

``` csharp
[DataMemberAttribute]
public string ReportId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReportId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetReportConfigurationDataRequest Class](getreportconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

