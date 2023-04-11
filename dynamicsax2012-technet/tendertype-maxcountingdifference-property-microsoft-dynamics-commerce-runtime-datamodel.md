---
title: TenderType.MaxCountingDifference Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaxCountingDifference Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaxCountingDifference
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maxcountingdifference(v=AX.60)
ms:contentKeyID: 65320561
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaxCountingDifference
dev_langs:
- CSharp
- C++
- VB
---

# MaxCountingDifference Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("MAXCOUNTINGDIFFERENCE")> _
Public Property MaxCountingDifference As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MaxCountingDifference

instance.MaxCountingDifference = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("MAXCOUNTINGDIFFERENCE")]
public decimal MaxCountingDifference { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"MAXCOUNTINGDIFFERENCE")]
public:
property Decimal MaxCountingDifference {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

