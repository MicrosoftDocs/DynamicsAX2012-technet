---
title: ShiftTenderLine.CardTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CardTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.cardtypeid(v=AX.60)
ms:contentKeyID: 62214673
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.CardTypeId
dev_langs:
- CSharp
- C++
- VB
---

# CardTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets card type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDTYPEID")> _
<DataMemberAttribute> _
Public Property CardTypeId As String
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As String

value = instance.CardTypeId

instance.CardTypeId = value
```

``` csharp
[ColumnAttribute("CARDTYPEID")]
[DataMemberAttribute]
public string CardTypeId { get; set; }
```

``` c++
[ColumnAttribute(L"CARDTYPEID")]
[DataMemberAttribute]
public:
property String^ CardTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

