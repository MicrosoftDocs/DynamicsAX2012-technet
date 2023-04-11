---
title: TaxCodeInterval.TaxUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxunit(v=AX.60)
ms:contentKeyID: 62203696
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxUnit
dev_langs:
- CSharp
- C++
- VB
---

# TaxUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tax unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXUNIT")> _
<DataMemberAttribute> _
Public Property TaxUnit As String
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As String

value = instance.TaxUnit
```

``` csharp
[ColumnAttribute("TAXUNIT")]
[DataMemberAttribute]
public string TaxUnit { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXUNIT")]
[DataMemberAttribute]
public:
property String^ TaxUnit {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

