---
title: BusinessIntelligenceManager.GetSupportedReports Method (String, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetSupportedReports Method (String, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.GetSupportedReports(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.getsupportedreports(v=AX.60)
ms:contentKeyID: 65316527
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSupportedReports Method (String, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetSupportedReports ( _
    locale As String, _
    settings As QueryResultSettings _
) As ReportDataSet
'Usage
Dim instance As BusinessIntelligenceManager
Dim locale As String
Dim settings As QueryResultSettings
Dim returnValue As ReportDataSet

returnValue = instance.GetSupportedReports(locale, _
    settings)
```

``` csharp
public ReportDataSet GetSupportedReports(
    string locale,
    QueryResultSettings settings
)
```

``` c++
public:
ReportDataSet^ GetSupportedReports(
    String^ locale, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetSupportedReports Overload](businessintelligencemanager-getsupportedreports-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

