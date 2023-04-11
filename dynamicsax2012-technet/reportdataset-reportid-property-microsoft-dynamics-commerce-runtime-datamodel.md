---
title: ReportDataSet.ReportId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReportId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.ReportId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportdataset.reportid(v=AX.60)
ms:contentKeyID: 62203366
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.ReportId
dev_langs:
- CSharp
- C++
- VB
---

# ReportId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the report id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<KeyAttribute> _
Public Property ReportId As String
    Get
    Set
'Usage
Dim instance As ReportDataSet
Dim value As String

value = instance.ReportId

instance.ReportId = value
```

``` csharp
[DataMemberAttribute]
[KeyAttribute]
public string ReportId { get; set; }
```

``` c++
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ ReportId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReportDataSet Class](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

