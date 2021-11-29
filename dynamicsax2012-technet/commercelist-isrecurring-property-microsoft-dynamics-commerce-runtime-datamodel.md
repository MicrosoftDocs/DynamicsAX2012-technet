---
title: CommerceList.IsRecurring Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRecurring Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.IsRecurring
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelist.isrecurring(v=AX.60)
ms:contentKeyID: 62203487
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList.IsRecurring
dev_langs:
- CSharp
- C++
- VB
---

# IsRecurring Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the commerce list is recurring.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsRecurring As Boolean
    Get
    Set
'Usage
Dim instance As CommerceList
Dim value As Boolean

value = instance.IsRecurring

instance.IsRecurring = value
```

``` csharp
[DataMemberAttribute]
public bool IsRecurring { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsRecurring {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommerceList Class](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

