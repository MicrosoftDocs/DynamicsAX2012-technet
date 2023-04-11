---
title: ReportConfiguration.DataSourceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataSourceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.DataSourceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.datasourcetype(v=AX.60)
ms:contentKeyID: 62212743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.DataSourceType
dev_langs:
- CSharp
- C++
- VB
---

# DataSourceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of datasource. Possible values are OLTP or OLAP.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property DataSourceType As String
    Get
    Set
'Usage
Dim instance As ReportConfiguration
Dim value As String

value = instance.DataSourceType

instance.DataSourceType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TYPE")]
public string DataSourceType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property String^ DataSourceType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The type of the report.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

