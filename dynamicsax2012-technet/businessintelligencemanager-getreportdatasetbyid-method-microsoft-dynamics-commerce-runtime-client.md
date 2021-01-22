---
title: BusinessIntelligenceManager.GetReportDataSetById Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReportDataSetById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.GetReportDataSetById(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.getreportdatasetbyid(v=AX.60)
ms:contentKeyID: 65320343
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.GetReportDataSetById
dev_langs:
- CSharp
- C++
- VB
---

# GetReportDataSetById Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReportDataSetById ( _
    reportId As String _
) As ReportDataSet
'Usage
Dim instance As BusinessIntelligenceManager
Dim reportId As String
Dim returnValue As ReportDataSet

returnValue = instance.GetReportDataSetById(reportId)
```

``` csharp
public ReportDataSet GetReportDataSetById(
    string reportId
)
```

``` c++
public:
ReportDataSet^ GetReportDataSetById(
    String^ reportId
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

