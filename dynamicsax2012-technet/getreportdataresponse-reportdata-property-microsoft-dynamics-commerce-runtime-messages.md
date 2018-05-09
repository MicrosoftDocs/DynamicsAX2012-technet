---
title: GetReportDataResponse.ReportData Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ReportData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataResponse.ReportData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getreportdataresponse.reportdata(v=AX.60)
ms:contentKeyID: 62212600
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReportDataResponse.ReportData
dev_langs:
- CSharp
- C++
- VB
---

# ReportData Property

Gets output dataset.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportData As ReportDataSet
    Get
    Private Set
'Usage
Dim instance As GetReportDataResponse
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
Returns [DataTable](https://technet.microsoft.com/en-us/library/9186hy08\(v=ax.60\)).  

## See Also

#### Reference

[GetReportDataResponse Class](getreportdataresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

