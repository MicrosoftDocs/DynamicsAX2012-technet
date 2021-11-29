---
title: TillLayout.ReportZones Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReportZones Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReportZones
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.reportzones(v=AX.60)
ms:contentKeyID: 62205387
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReportZones
dev_langs:
- CSharp
- C++
- VB
---

# ReportZones Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of report zones.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReportZones As ICollection(Of ReportZone)
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As ICollection(Of ReportZone)

value = instance.ReportZones

instance.ReportZones = value
```

``` csharp
[DataMemberAttribute]
public ICollection<ReportZone> ReportZones { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ReportZone^>^ ReportZones {
    ICollection<ReportZone^>^ get ();
    void set (ICollection<ReportZone^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ReportZone](reportzone-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

