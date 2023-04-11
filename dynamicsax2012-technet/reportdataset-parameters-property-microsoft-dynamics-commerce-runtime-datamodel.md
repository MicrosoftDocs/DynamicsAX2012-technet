---
title: ReportDataSet.Parameters Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Parameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.Parameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportdataset.parameters(v=AX.60)
ms:contentKeyID: 62203463
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet.Parameters
dev_langs:
- CSharp
- C++
- VB
---

# Parameters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the report parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Parameters As IEnumerable(Of CommerceProperty)
    Get
    Set
'Usage
Dim instance As ReportDataSet
Dim value As IEnumerable(Of CommerceProperty)

value = instance.Parameters

instance.Parameters = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<CommerceProperty> Parameters { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<CommerceProperty^>^ Parameters {
    IEnumerable<CommerceProperty^>^ get ();
    void set (IEnumerable<CommerceProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ReportDataSet Class](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

