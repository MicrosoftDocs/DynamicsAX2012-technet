---
title: PeriodicDiscount.MixAndMatchNumberOfTimeApplicable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchNumberOfTimeApplicable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchNumberOfTimeApplicable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchnumberoftimeapplicable(v=AX.60)
ms:contentKeyID: 49838561
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchNumberOfTimeApplicable
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchNumberOfTimeApplicable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of times this mix and match discount can be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NUMBEROFTIMESAPPLICABLE")> _
<DataMemberAttribute> _
Public Property MixAndMatchNumberOfTimeApplicable As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.MixAndMatchNumberOfTimeApplicable
```

``` csharp
[ColumnAttribute("NUMBEROFTIMESAPPLICABLE")]
[DataMemberAttribute]
public int MixAndMatchNumberOfTimeApplicable { get; internal set; }
```

``` c++
[ColumnAttribute(L"NUMBEROFTIMESAPPLICABLE")]
[DataMemberAttribute]
public:
property int MixAndMatchNumberOfTimeApplicable {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

