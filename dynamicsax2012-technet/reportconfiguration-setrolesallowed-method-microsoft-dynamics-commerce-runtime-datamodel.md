---
title: ReportConfiguration.SetRolesAllowed Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetRolesAllowed Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.SetRolesAllowed(System.Collections.ObjectModel.ReadOnlyCollection{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reportconfiguration.setrolesallowed(v=AX.60)
ms:contentKeyID: 62210255
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportConfiguration.SetRolesAllowed
dev_langs:
- CSharp
- C++
- VB
---

# SetRolesAllowed Method

Sets the roles allowed for this report.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetRolesAllowed ( _
    rolesAllowed As ReadOnlyCollection(Of String) _
)
'Usage
Dim instance As ReportConfiguration
Dim rolesAllowed As ReadOnlyCollection(Of String)

instance.SetRolesAllowed(rolesAllowed)
```

``` csharp
public void SetRolesAllowed(
    ReadOnlyCollection<string> rolesAllowed
)
```

``` c++
public:
void SetRolesAllowed(
    ReadOnlyCollection<String^>^ rolesAllowed
)
```

#### Parameters

  - rolesAllowed  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ReportConfiguration Class](reportconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

