---
title: TenderType.TakenToBank Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TakenToBank Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.TakenToBank
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.takentobank(v=AX.60)
ms:contentKeyID: 62215048
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.TakenToBank
dev_langs:
- CSharp
- C++
- VB
---

# TakenToBank Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the taken to bank value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAKENTOBANK")> _
Public Property TakenToBank As Integer
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.TakenToBank

instance.TakenToBank = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAKENTOBANK")]
public int TakenToBank { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAKENTOBANK")]
public:
property int TakenToBank {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

