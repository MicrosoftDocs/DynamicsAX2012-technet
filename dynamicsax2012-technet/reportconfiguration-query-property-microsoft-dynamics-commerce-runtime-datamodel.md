---
title: ReportConfiguration.Query Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Query Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.Query
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.query(v=AX.60)
ms:contentKeyID: 62212611
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.Query
dev_langs:
- CSharp
- C++
- VB
---

# Query Property

Gets or sets the datasource.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATASOURCE")> _
<DataMemberAttribute> _
Public Property Query As String
    Get
    Set
'Usage
Dim instance As ReportConfiguration
Dim value As String

value = instance.Query

instance.Query = value
```

``` csharp
[ColumnAttribute("DATASOURCE")]
[DataMemberAttribute]
public string Query { get; set; }
```

``` c++
[ColumnAttribute(L"DATASOURCE")]
[DataMemberAttribute]
public:
property String^ Query {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The report query.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

