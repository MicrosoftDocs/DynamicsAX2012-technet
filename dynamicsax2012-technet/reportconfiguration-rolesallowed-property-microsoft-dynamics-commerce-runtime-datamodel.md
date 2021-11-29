---
title: ReportConfiguration.RolesAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RolesAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.RolesAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.rolesallowed(v=AX.60)
ms:contentKeyID: 62212116
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.RolesAllowed
dev_langs:
- CSharp
- C++
- VB
---

# RolesAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the roles allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RolesAllowed As ReadOnlyCollection(Of String)
    Get
    Friend Set
'Usage
Dim instance As ReportConfiguration
Dim value As ReadOnlyCollection(Of String)

value = instance.RolesAllowed
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<string> RolesAllowed { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ RolesAllowed {
    ReadOnlyCollection<String^>^ get ();
    internal: void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The roles allowed for this report.  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

