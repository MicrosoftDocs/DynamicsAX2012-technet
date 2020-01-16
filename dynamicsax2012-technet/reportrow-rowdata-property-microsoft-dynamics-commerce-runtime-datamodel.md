---
title: ReportRow.RowData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RowData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportRow.RowData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportrow.rowdata(v=AX.60)
ms:contentKeyID: 62202523
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportRow.RowData
dev_langs:
- CSharp
- C++
- VB
---

# RowData Property

Gets the collection of name value pairs in this row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RowData As Collection(Of CommerceProperty)
    Get
    Private Set
'Usage
Dim instance As ReportRow
Dim value As Collection(Of CommerceProperty)

value = instance.RowData
```

``` csharp
[DataMemberAttribute]
public Collection<CommerceProperty> RowData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<CommerceProperty^>^ RowData {
    Collection<CommerceProperty^>^ get ();
    private: void set (Collection<CommerceProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ReportRow Class](reportrow-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

