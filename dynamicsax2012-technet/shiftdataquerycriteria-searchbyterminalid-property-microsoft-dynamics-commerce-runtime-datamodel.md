---
title: ShiftDataQueryCriteria.SearchByTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchByTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.SearchByTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftdataquerycriteria.searchbyterminalid(v=AX.60)
ms:contentKeyID: 65319753
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.SearchByTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# SearchByTerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether searching by terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchByTerminalId As Boolean
    Get
    Set
'Usage
Dim instance As ShiftDataQueryCriteria
Dim value As Boolean

value = instance.SearchByTerminalId

instance.SearchByTerminalId = value
```

``` csharp
[DataMemberAttribute]
public bool SearchByTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SearchByTerminalId {
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

