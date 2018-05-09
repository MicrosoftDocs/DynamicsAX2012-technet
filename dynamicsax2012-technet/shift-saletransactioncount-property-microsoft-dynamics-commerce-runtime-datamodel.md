---
title: Shift.SaleTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SaleTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SaleTransactionCount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.saletransactioncount(v=AX.60)
ms:contentKeyID: 62208015
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.SaleTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# SaleTransactionCount Property

Gets or sets count of sales transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESCOUNT")> _
Public Property SaleTransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.SaleTransactionCount

instance.SaleTransactionCount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESCOUNT")]
public int SaleTransactionCount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESCOUNT")]
public:
property int SaleTransactionCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

