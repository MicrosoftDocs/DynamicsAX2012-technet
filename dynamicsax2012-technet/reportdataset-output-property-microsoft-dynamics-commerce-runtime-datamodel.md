---
title: ReportDataSet.Output Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Output Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.Output
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportdataset.output(v=AX.60)
ms:contentKeyID: 62202736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.Output
dev_langs:
- CSharp
- C++
- VB
---

# Output Property

Gets or sets the report output collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Output As Collection(Of ReportRow)
    Get
    Set
'Usage
Dim instance As ReportDataSet
Dim value As Collection(Of ReportRow)

value = instance.Output

instance.Output = value
```

``` csharp
[DataMemberAttribute]
public Collection<ReportRow> Output { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ReportRow^>^ Output {
    Collection<ReportRow^>^ get ();
    void set (Collection<ReportRow^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ReportRow](reportrow-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ReportDataSet Class](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

