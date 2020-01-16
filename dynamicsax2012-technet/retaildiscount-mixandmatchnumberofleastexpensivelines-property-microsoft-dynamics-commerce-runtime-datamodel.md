---
title: RetailDiscount.MixAndMatchNumberOfLeastExpensiveLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchNumberOfLeastExpensiveLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchNumberOfLeastExpensiveLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscount.mixandmatchnumberofleastexpensivelines(v=AX.60)
ms:contentKeyID: 62208966
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount.MixAndMatchNumberOfLeastExpensiveLines
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchNumberOfLeastExpensiveLines Property

Gets or sets the number of least expensive lines to discount on a mix and match set if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NOOFLEASTEXPENSIVELINES")> _
Public Property MixAndMatchNumberOfLeastExpensiveLines As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscount
Dim value As Integer

value = instance.MixAndMatchNumberOfLeastExpensiveLines

instance.MixAndMatchNumberOfLeastExpensiveLines = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NOOFLEASTEXPENSIVELINES")]
public int MixAndMatchNumberOfLeastExpensiveLines { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NOOFLEASTEXPENSIVELINES")]
public:
property int MixAndMatchNumberOfLeastExpensiveLines {
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

