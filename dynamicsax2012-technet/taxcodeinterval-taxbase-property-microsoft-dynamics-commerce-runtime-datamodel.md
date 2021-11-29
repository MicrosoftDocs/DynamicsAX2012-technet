---
title: TaxCodeInterval.TaxBase Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxBase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxbase(v=AX.60)
ms:contentKeyID: 62214355
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxBase
dev_langs:
- CSharp
- C++
- VB
---

# TaxBase Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax base.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXBASE")> _
<DataMemberAttribute> _
Public Property TaxBase As Integer
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Integer

value = instance.TaxBase
```

``` csharp
[ColumnAttribute("TAXBASE")]
[DataMemberAttribute]
public int TaxBase { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXBASE")]
[DataMemberAttribute]
public:
property int TaxBase {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

