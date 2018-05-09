---
title: BusinessIntelligenceManager.GetReportData Method (String, IEnumerable(CommerceProperty), String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetReportData Method (String, IEnumerable(CommerceProperty), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.GetReportData(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.getreportdata(v=AX.60)
ms:contentKeyID: 65316242
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReportData Method (String, IEnumerable(CommerceProperty), String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetReportData ( _
    reportId As String, _
    reportParameters As IEnumerable(Of CommerceProperty), _
    locale As String _
) As ReportDataSet
'Usage
Dim instance As BusinessIntelligenceManager
Dim reportId As String
Dim reportParameters As IEnumerable(Of CommerceProperty)
Dim locale As String
Dim returnValue As ReportDataSet

returnValue = instance.GetReportData(reportId, _
    reportParameters, locale)
```

``` csharp
public ReportDataSet GetReportData(
    string reportId,
    IEnumerable<CommerceProperty> reportParameters,
    string locale
)
```

``` c++
public:
ReportDataSet^ GetReportData(
    String^ reportId, 
    IEnumerable<CommerceProperty^>^ reportParameters, 
    String^ locale
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

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetReportData Overload](businessintelligencemanager-getreportdata-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

