---
title: Shift.CurrentStaffId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrentStaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CurrentStaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.currentstaffid(v=AX.60)
ms:contentKeyID: 62207721
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.CurrentStaffId
dev_langs:
- CSharp
- C++
- VB
---

# CurrentStaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the current staff id of Shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CURRENTSTAFFID")> _
Public Property CurrentStaffId As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.CurrentStaffId

instance.CurrentStaffId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CURRENTSTAFFID")]
public string CurrentStaffId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CURRENTSTAFFID")]
public:
property String^ CurrentStaffId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

