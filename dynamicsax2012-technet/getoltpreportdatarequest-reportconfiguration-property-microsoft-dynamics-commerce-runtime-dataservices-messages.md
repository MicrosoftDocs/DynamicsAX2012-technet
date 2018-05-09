---
title: GetOLTPReportDataRequest.ReportConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReportConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOLTPReportDataRequest.ReportConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getoltpreportdatarequest.reportconfiguration(v=AX.60)
ms:contentKeyID: 65319191
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetOLTPReportDataRequest.ReportConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ReportConfiguration Property

Gets the id of the report.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportConfiguration As ReportConfiguration
    Get
    Private Set
'Usage
Dim instance As GetOLTPReportDataRequest
Dim value As ReportConfiguration

value = instance.ReportConfiguration
```

``` csharp
[DataMemberAttribute]
public ReportConfiguration ReportConfiguration { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReportConfiguration^ ReportConfiguration {
    ReportConfiguration^ get ();
    private: void set (ReportConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReportConfiguration](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetOLTPReportDataRequest Class](getoltpreportdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

