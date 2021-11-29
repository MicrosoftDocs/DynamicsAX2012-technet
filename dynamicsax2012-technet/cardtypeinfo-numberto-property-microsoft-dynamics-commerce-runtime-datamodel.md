---
title: CardTypeInfo.NumberTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.NumberTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.numberto(v=AX.60)
ms:contentKeyID: 62213339
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.NumberTo
dev_langs:
- CSharp
- C++
- VB
---

# NumberTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card number to.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDNUMBERTO")> _
<DataMemberAttribute> _
Public Property NumberTo As String
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As String

value = instance.NumberTo

instance.NumberTo = value
```

``` csharp
[ColumnAttribute("CARDNUMBERTO")]
[DataMemberAttribute]
public string NumberTo { get; set; }
```

``` c++
[ColumnAttribute(L"CARDNUMBERTO")]
[DataMemberAttribute]
public:
property String^ NumberTo {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

