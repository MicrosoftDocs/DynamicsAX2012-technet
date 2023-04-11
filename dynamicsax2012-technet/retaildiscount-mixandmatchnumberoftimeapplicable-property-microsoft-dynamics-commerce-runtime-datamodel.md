---
title: RetailDiscount.MixAndMatchNumberOfTimeApplicable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchNumberOfTimeApplicable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchNumberOfTimeApplicable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.mixandmatchnumberoftimeapplicable(v=AX.60)
ms:contentKeyID: 62214845
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchNumberOfTimeApplicable
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchNumberOfTimeApplicable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of times this mix and match discount can be applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NUMBEROFTIMESAPPLICABLE")> _
Public Property MixAndMatchNumberOfTimeApplicable As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Integer

value = instance.MixAndMatchNumberOfTimeApplicable

instance.MixAndMatchNumberOfTimeApplicable = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NUMBEROFTIMESAPPLICABLE")]
public int MixAndMatchNumberOfTimeApplicable { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NUMBEROFTIMESAPPLICABLE")]
public:
property int MixAndMatchNumberOfTimeApplicable {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscount Class](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

