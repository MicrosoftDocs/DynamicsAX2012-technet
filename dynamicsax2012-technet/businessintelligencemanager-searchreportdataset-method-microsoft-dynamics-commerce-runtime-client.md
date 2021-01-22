---
title: BusinessIntelligenceManager.SearchReportDataSet Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SearchReportDataSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.SearchReportDataSet(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.searchreportdataset(v=AX.60)
ms:contentKeyID: 65317171
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.SearchReportDataSet
dev_langs:
- CSharp
- C++
- VB
---

# SearchReportDataSet Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SearchReportDataSet ( _
    reportId As String, _
    parameters As IEnumerable(Of CommerceProperty), _
    locale As String _
) As ReportDataSet
'Usage
Dim instance As BusinessIntelligenceManager
Dim reportId As String
Dim parameters As IEnumerable(Of CommerceProperty)
Dim locale As String
Dim returnValue As ReportDataSet

returnValue = instance.SearchReportDataSet(reportId, _
    parameters, locale)
```

``` csharp
public ReportDataSet SearchReportDataSet(
    string reportId,
    IEnumerable<CommerceProperty> parameters,
    string locale
)
```

``` c++
public:
ReportDataSet^ SearchReportDataSet(
    String^ reportId, 
    IEnumerable<CommerceProperty^>^ parameters, 
    String^ locale
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

