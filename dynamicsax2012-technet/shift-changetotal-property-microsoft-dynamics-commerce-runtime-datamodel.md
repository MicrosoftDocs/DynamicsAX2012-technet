---
title: Shift.ChangeTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ChangeTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.changetotal(v=AX.60)
ms:contentKeyID: 62211502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ChangeTotal
dev_langs:
- CSharp
- C++
- VB
---

# ChangeTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total of change amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overridable Property ChangeTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.ChangeTotal

instance.ChangeTotal = value
```

``` csharp
[DataMemberAttribute]
public virtual decimal ChangeTotal { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property Decimal ChangeTotal {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

