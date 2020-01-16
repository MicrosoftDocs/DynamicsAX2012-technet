---
title: GetReportDataServiceResponse.ReportData Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReportData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceResponse.ReportData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreportdataserviceresponse.reportdata(v=AX.60)
ms:contentKeyID: 62212005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReportDataServiceResponse.ReportData
dev_langs:
- CSharp
- C++
- VB
---

# ReportData Property

Gets the output report data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportData As ReportDataSet
    Get
    Private Set
'Usage
Dim instance As GetReportDataServiceResponse
Dim value As ReportDataSet

value = instance.ReportData
```

``` csharp
[DataMemberAttribute]
public ReportDataSet ReportData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReportDataSet^ ReportData {
    ReportDataSet^ get ();
    private: void set (ReportDataSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\)).  

## See Also

#### Reference

[GetReportDataServiceResponse Class](getreportdataserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

