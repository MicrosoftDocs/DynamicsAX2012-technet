---
title: Shift.LogOnTransactionCount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnTransactionCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.LogOnTransactionCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.logontransactioncount(v=AX.60)
ms:contentKeyID: 62211130
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.LogOnTransactionCount
dev_langs:
- CSharp
- C++
- VB
---

# LogOnTransactionCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets count of LogOn transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOGONSCOUNT")> _
<DataMemberAttribute> _
Public Property LogOnTransactionCount As Integer
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Integer

value = instance.LogOnTransactionCount

instance.LogOnTransactionCount = value
```

``` csharp
[ColumnAttribute("LOGONSCOUNT")]
[DataMemberAttribute]
public int LogOnTransactionCount { get; set; }
```

``` c++
[ColumnAttribute(L"LOGONSCOUNT")]
[DataMemberAttribute]
public:
property int LogOnTransactionCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

