---
title: BusinessIntelligenceManager.GetReportData Method (String, IEnumerable(CommerceProperty)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReportData Method (String, IEnumerable(CommerceProperty))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.GetReportData(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.getreportdata(v=AX.60)
ms:contentKeyID: 65320797
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReportData Method (String, IEnumerable(CommerceProperty))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReportData ( _
    reportId As String, _
    reportParameters As IEnumerable(Of CommerceProperty) _
) As ReportDataSet
'Usage
Dim instance As BusinessIntelligenceManager
Dim reportId As String
Dim reportParameters As IEnumerable(Of CommerceProperty)
Dim returnValue As ReportDataSet

returnValue = instance.GetReportData(reportId, _
    reportParameters)
```

``` csharp
public ReportDataSet GetReportData(
    string reportId,
    IEnumerable<CommerceProperty> reportParameters
)
```

``` c++
public:
ReportDataSet^ GetReportData(
    String^ reportId, 
    IEnumerable<CommerceProperty^>^ reportParameters
)
```

#### Parameters

  - reportId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reportParameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetReportData Overload](businessintelligencemanager-getreportdata-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

