---
title: OrgUnit Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnit Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit(v=AX.60)
ms:contentKeyID: 62211286
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnit Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a organization unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "STORENAME", IsDescending := False,  _
    Priority := )> _
<DataContractAttribute> _
<DefaultSortOrderAttribute(ColumnName := "STORENUMBER", IsDescending := False,  _
    Priority := )> _
Public Class OrgUnit _
    Inherits Channel
'Usage
Dim instance As OrgUnit
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "STORENAME", IsDescending = false, 
    Priority = )]
[DataContractAttribute]
[DefaultSortOrderAttribute(ColumnName = "STORENUMBER", IsDescending = false, 
    Priority = )]
public class OrgUnit : Channel
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"STORENAME", IsDescending = false, 
    Priority = )]
[DataContractAttribute]
[DefaultSortOrderAttribute(ColumnName = L"STORENUMBER", IsDescending = false, 
    Priority = )]
public ref class OrgUnit : public Channel
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

