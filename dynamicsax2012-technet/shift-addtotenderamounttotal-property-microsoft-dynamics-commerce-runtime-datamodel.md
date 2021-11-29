---
title: Shift.AddToTenderAmountTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddToTenderAmountTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.AddToTenderAmountTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.addtotenderamounttotal(v=AX.60)
ms:contentKeyID: 62210901
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.AddToTenderAmountTotal
dev_langs:
- CSharp
- C++
- VB
---

# AddToTenderAmountTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total amount added to tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overridable Property AddToTenderAmountTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.AddToTenderAmountTotal

instance.AddToTenderAmountTotal = value
```

``` csharp
[DataMemberAttribute]
public virtual decimal AddToTenderAmountTotal { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property Decimal AddToTenderAmountTotal {
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

