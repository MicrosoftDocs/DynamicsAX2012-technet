---
title: ReportConfiguration.Parameters Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Parameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.Parameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.parameters(v=AX.60)
ms:contentKeyID: 62215089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.Parameters
dev_langs:
- CSharp
- C++
- VB
---

# Parameters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PARAMETERS")> _
<DataMemberAttribute> _
Public Property Parameters As IEnumerable(Of CommerceProperty)
    Get
    Private Set
'Usage
Dim instance As ReportConfiguration
Dim value As IEnumerable(Of CommerceProperty)

value = instance.Parameters
```

``` csharp
[ColumnAttribute("PARAMETERS")]
[DataMemberAttribute]
public IEnumerable<CommerceProperty> Parameters { get; private set; }
```

``` c++
[ColumnAttribute(L"PARAMETERS")]
[DataMemberAttribute]
public:
property IEnumerable<CommerceProperty^>^ Parameters {
    IEnumerable<CommerceProperty^>^ get ();
    private: void set (IEnumerable<CommerceProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceProperty](commerceproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The report parameters.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

