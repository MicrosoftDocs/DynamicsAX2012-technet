---
title: Shift.SuspendedTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SuspendedTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SuspendedTransactionCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.suspendedtransactioncount(v=AX.60)
ms:contentKeyID: 62213239
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SuspendedTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# SuspendedTransactionCount Property

Gets or sets count of suspended transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SUSPENDEDCOUNT")> _
<DataMemberAttribute> _
Public Property SuspendedTransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.SuspendedTransactionCount

instance.SuspendedTransactionCount = value
```

``` csharp
[ColumnAttribute("SUSPENDEDCOUNT")]
[DataMemberAttribute]
public int SuspendedTransactionCount { get; set; }
```

``` c++
[ColumnAttribute(L"SUSPENDEDCOUNT")]
[DataMemberAttribute]
public:
property int SuspendedTransactionCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

This field won't be persisted into DB and is only required by X report.

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

