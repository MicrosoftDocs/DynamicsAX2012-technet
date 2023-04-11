---
title: CardTypeInfo.CheckModulus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CheckModulus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CheckModulus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.checkmodulus(v=AX.60)
ms:contentKeyID: 62209495
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CheckModulus
dev_langs:
- CSharp
- C++
- VB
---

# CheckModulus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to check modulus.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHECKMODULUS")> _
Public Property CheckModulus As Boolean
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As Boolean

value = instance.CheckModulus

instance.CheckModulus = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHECKMODULUS")]
public bool CheckModulus { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHECKMODULUS")]
public:
property bool CheckModulus {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

