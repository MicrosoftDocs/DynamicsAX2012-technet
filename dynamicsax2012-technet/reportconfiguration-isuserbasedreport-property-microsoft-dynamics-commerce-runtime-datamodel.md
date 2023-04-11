---
title: ReportConfiguration.IsUserBasedReport Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsUserBasedReport Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.IsUserBasedReport
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.isuserbasedreport(v=AX.60)
ms:contentKeyID: 62211977
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.IsUserBasedReport
dev_langs:
- CSharp
- C++
- VB
---

# IsUserBasedReport Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the report is user based.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsUserBasedReport As Boolean
    Get
    Set
'Usage
Dim instance As ReportConfiguration
Dim value As Boolean

value = instance.IsUserBasedReport

instance.IsUserBasedReport = value
```

``` csharp
[DataMemberAttribute]
public bool IsUserBasedReport { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsUserBasedReport {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The bool indicating if it is a user based report.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

