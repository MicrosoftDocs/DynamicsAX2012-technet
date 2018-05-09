---
title: Shift.NoSaleTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NoSaleTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.NoSaleTransactionCount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.nosaletransactioncount(v=AX.60)
ms:contentKeyID: 62213363
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.NoSaleTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# NoSaleTransactionCount Property

Gets or sets count of no sales transactions (Open Cash Drawer).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NOSALECOUNT")> _
Public Property NoSaleTransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.NoSaleTransactionCount

instance.NoSaleTransactionCount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NOSALECOUNT")]
public int NoSaleTransactionCount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NOSALECOUNT")]
public:
property int NoSaleTransactionCount {
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

