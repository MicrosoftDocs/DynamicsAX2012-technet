---
title: ReportConfiguration.ReportId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReportId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.ReportId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.reportid(v=AX.60)
ms:contentKeyID: 62212875
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.ReportId
dev_langs:
- CSharp
- C++
- VB
---

# ReportId Property

Gets or sets the report identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REPORTID")> _
<DataMemberAttribute> _
Public Property ReportId As String
    Get
    Set
'Usage
Dim instance As ReportConfiguration
Dim value As String

value = instance.ReportId

instance.ReportId = value
```

``` csharp
[ColumnAttribute("REPORTID")]
[DataMemberAttribute]
public string ReportId { get; set; }
```

``` c++
[ColumnAttribute(L"REPORTID")]
[DataMemberAttribute]
public:
property String^ ReportId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The report id.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

