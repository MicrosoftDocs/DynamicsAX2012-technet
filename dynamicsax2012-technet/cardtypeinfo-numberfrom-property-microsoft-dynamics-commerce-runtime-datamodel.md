---
title: CardTypeInfo.NumberFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.NumberFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.numberfrom(v=AX.60)
ms:contentKeyID: 62212978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.NumberFrom
dev_langs:
- CSharp
- C++
- VB
---

# NumberFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card number from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CARDNUMBERFROM")> _
Public Property NumberFrom As String
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As String

value = instance.NumberFrom

instance.NumberFrom = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CARDNUMBERFROM")]
public string NumberFrom { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CARDNUMBERFROM")]
public:
property String^ NumberFrom {
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

