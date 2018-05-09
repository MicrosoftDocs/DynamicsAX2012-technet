---
title: TransactionLog.TransactionTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog.TransactionTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transactionlog.transactiontypevalue(v=AX.60)
ms:contentKeyID: 62208627
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog.TransactionTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTypeValue Property

Gets or sets the value of the transaction type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionTypeValue As Integer
    Get
    Set
'Usage
Dim instance As TransactionLog
Dim value As Integer

value = instance.TransactionTypeValue

instance.TransactionTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int TransactionTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TransactionTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TransactionLog Class](transactionlog-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

