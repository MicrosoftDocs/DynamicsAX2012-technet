---
title: TaxCodeInterval.TaxLimitBase Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxLimitBase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitBase
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxlimitbase(v=AX.60)
ms:contentKeyID: 62201891
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitBase
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitBase Property

Gets the tax limit base.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXLIMITBASE")> _
Public Property TaxLimitBase As Integer
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Integer

value = instance.TaxLimitBase
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXLIMITBASE")]
public int TaxLimitBase { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXLIMITBASE")]
public:
property int TaxLimitBase {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

