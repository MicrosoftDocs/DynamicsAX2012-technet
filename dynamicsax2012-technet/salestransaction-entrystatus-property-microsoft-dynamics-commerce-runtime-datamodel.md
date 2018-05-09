---
title: SalesTransaction.EntryStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EntryStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.entrystatus(v=AX.60)
ms:contentKeyID: 62209105
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.EntryStatus
dev_langs:
- CSharp
- C++
- VB
---

# EntryStatus Property

Gets or sets the EntryStatus.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ENTRYSTATUS")> _
Public Property EntryStatus As TransactionStatus
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As TransactionStatus

value = instance.EntryStatus

instance.EntryStatus = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ENTRYSTATUS")]
public TransactionStatus EntryStatus { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ENTRYSTATUS")]
public:
property TransactionStatus EntryStatus {
    TransactionStatus get ();
    void set (TransactionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

