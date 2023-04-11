---
title: TaxCodeUnit.TaxRoundOffType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxRoundOffType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit.TaxRoundOffType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeunit.taxroundofftype(v=AX.60)
ms:contentKeyID: 62210069
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit.TaxRoundOffType
dev_langs:
- CSharp
- C++
- VB
---

# TaxRoundOffType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of the tax round off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXROUNDOFFTYPE")> _
Public Property TaxRoundOffType As Integer
    Get
    Friend Set
'Usage
Dim instance As TaxCodeUnit
Dim value As Integer

value = instance.TaxRoundOffType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXROUNDOFFTYPE")]
public int TaxRoundOffType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXROUNDOFFTYPE")]
public:
property int TaxRoundOffType {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The type of the tax round off.  

## See Also

#### Reference

[TaxCodeUnit Class](taxcodeunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

