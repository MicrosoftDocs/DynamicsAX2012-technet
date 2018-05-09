---
title: ReportRow.SetRowData Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetRowData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportRow.SetRowData(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceProperty})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reportrow.setrowdata(v=AX.60)
ms:contentKeyID: 62203149
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportRow.SetRowData
dev_langs:
- CSharp
- C++
- VB
---

# SetRowData Method

Set name value pairs for this row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetRowData ( _
    rowData As Collection(Of CommerceProperty) _
)
'Usage
Dim instance As ReportRow
Dim rowData As Collection(Of CommerceProperty)

instance.SetRowData(rowData)
```

``` csharp
public void SetRowData(
    Collection<CommerceProperty> rowData
)
```

``` c++
public:
void SetRowData(
    Collection<CommerceProperty^>^ rowData
)
```

#### Parameters

  - rowData  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ReportRow Class](reportrow-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

