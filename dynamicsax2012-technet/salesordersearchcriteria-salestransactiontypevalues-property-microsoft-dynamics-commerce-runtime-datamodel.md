---
title: SalesOrderSearchCriteria.SalesTransactionTypeValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTransactionTypeValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SalesTransactionTypeValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.salestransactiontypevalues(v=AX.60)
ms:contentKeyID: 62208701
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SalesTransactionTypeValues
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionTypeValues Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection of transaction type's values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesTransactionTypeValues As IEnumerable(Of Integer)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As IEnumerable(Of Integer)

value = instance.SalesTransactionTypeValues

instance.SalesTransactionTypeValues = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<int> SalesTransactionTypeValues { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<int>^ SalesTransactionTypeValues {
    IEnumerable<int>^ get ();
    void set (IEnumerable<int>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

