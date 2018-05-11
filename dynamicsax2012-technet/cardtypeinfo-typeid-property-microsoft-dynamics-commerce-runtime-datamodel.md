﻿---
title: CardTypeInfo.TypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.TypeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.typeid(v=AX.60)
ms:contentKeyID: 62209679
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.TypeId
dev_langs:
- CSharp
- C++
- VB
---

# TypeId Property

Gets or sets the card type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDTYPEID")> _
<DataMemberAttribute> _
Public Property TypeId As String
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As String

value = instance.TypeId

instance.TypeId = value
```

``` csharp
[ColumnAttribute("CARDTYPEID")]
[DataMemberAttribute]
public string TypeId { get; set; }
```

``` c++
[ColumnAttribute(L"CARDTYPEID")]
[DataMemberAttribute]
public:
property String^ TypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
