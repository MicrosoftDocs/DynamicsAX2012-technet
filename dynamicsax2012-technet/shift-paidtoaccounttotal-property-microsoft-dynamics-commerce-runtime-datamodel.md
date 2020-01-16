---
title: Shift.PaidToAccountTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaidToAccountTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.PaidToAccountTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.paidtoaccounttotal(v=AX.60)
ms:contentKeyID: 62212538
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.PaidToAccountTotal
dev_langs:
- CSharp
- C++
- VB
---

# PaidToAccountTotal Property

Gets or sets total of paid to accounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PAIDTOACCOUNTTOTAL")> _
<DataMemberAttribute> _
Public Property PaidToAccountTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.PaidToAccountTotal

instance.PaidToAccountTotal = value
```

``` csharp
[ColumnAttribute("PAIDTOACCOUNTTOTAL")]
[DataMemberAttribute]
public decimal PaidToAccountTotal { get; set; }
```

``` c++
[ColumnAttribute(L"PAIDTOACCOUNTTOTAL")]
[DataMemberAttribute]
public:
property Decimal PaidToAccountTotal {
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

