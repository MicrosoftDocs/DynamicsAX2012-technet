---
title: CommerceListLine.IsRecurring Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRecurring Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.IsRecurring
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commercelistline.isrecurring(v=AX.60)
ms:contentKeyID: 62206327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine.IsRecurring
dev_langs:
- CSharp
- C++
- VB
---

# IsRecurring Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether commerce list line is recurring.

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
Dim instance As CommerceListLine
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

[CommerceListLine Class](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

