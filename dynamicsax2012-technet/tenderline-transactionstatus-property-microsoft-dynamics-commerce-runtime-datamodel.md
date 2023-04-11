---
title: TenderLine.TransactionStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.TransactionStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderline.transactionstatus(v=AX.60)
ms:contentKeyID: 62213753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.TransactionStatus
dev_langs:
- CSharp
- C++
- VB
---

# TransactionStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction status of the tender line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TransactionStatus As TransactionStatus
    Get
'Usage
Dim instance As TenderLine
Dim value As TransactionStatus

value = instance.TransactionStatus
```

``` csharp
[IgnoreDataMemberAttribute]
public TransactionStatus TransactionStatus { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property TransactionStatus TransactionStatus {
    TransactionStatus get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## Remarks

Should only used to persist tender line database.

## See Also

#### Reference

[TenderLine Class](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

