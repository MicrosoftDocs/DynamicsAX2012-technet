---
title: ReportConfiguration.SetReportParameters Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetReportParameters Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.SetReportParameters(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.setreportparameters(v=AX.60)
ms:contentKeyID: 65319336
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.SetReportParameters
dev_langs:
- CSharp
- C++
- VB
---

# SetReportParameters Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetReportParameters ( _
    reportParameters As IEnumerable(Of CommerceProperty) _
)
'Usage
Dim instance As ReportConfiguration
Dim reportParameters As IEnumerable(Of CommerceProperty)

instance.SetReportParameters(reportParameters)
```

``` csharp
public void SetReportParameters(
    IEnumerable<CommerceProperty> reportParameters
)
```

``` c++
public:
void SetReportParameters(
    IEnumerable<CommerceProperty^>^ reportParameters
)
```

#### Parameters

  - reportParameters  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

