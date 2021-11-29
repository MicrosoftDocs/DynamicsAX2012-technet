---
title: ShiftDataQueryCriteria.SearchByCurrentStaffId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchByCurrentStaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.SearchByCurrentStaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftdataquerycriteria.searchbycurrentstaffid(v=AX.60)
ms:contentKeyID: 65322770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.SearchByCurrentStaffId
dev_langs:
- CSharp
- C++
- VB
---

# SearchByCurrentStaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether searching by current staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchByCurrentStaffId As Boolean
    Get
    Set
'Usage
Dim instance As ShiftDataQueryCriteria
Dim value As Boolean

value = instance.SearchByCurrentStaffId

instance.SearchByCurrentStaffId = value
```

``` csharp
[DataMemberAttribute]
public bool SearchByCurrentStaffId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SearchByCurrentStaffId {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ShiftDataQueryCriteria Class](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

