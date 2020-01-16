---
title: SalesOrderSearchCriteria.TransactionStatusTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionStatusTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.TransactionStatusTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.transactionstatustypes(v=AX.60)
ms:contentKeyID: 62210718
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.TransactionStatusTypes
dev_langs:
- CSharp
- C++
- VB
---

# TransactionStatusTypes Property

Gets or sets a collection of transaction status type(s).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TransactionStatusTypes As IEnumerable(Of TransactionStatus)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As IEnumerable(Of TransactionStatus)

value = instance.TransactionStatusTypes

instance.TransactionStatusTypes = value
```

``` csharp
[IgnoreDataMemberAttribute]
public IEnumerable<TransactionStatus> TransactionStatusTypes { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property IEnumerable<TransactionStatus>^ TransactionStatusTypes {
    IEnumerable<TransactionStatus>^ get ();
    void set (IEnumerable<TransactionStatus>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransactionStatus](transactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

