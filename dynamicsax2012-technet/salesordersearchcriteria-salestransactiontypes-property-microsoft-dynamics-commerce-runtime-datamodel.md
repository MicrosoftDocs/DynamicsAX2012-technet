---
title: SalesOrderSearchCriteria.SalesTransactionTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTransactionTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SalesTransactionTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.salestransactiontypes(v=AX.60)
ms:contentKeyID: 62208447
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SalesTransactionTypes
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionTypes Property

Gets or sets a collection of transaction type(s).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property SalesTransactionTypes As IEnumerable(Of SalesTransactionType)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As IEnumerable(Of SalesTransactionType)

value = instance.SalesTransactionTypes

instance.SalesTransactionTypes = value
```

``` csharp
[IgnoreDataMemberAttribute]
public IEnumerable<SalesTransactionType> SalesTransactionTypes { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property IEnumerable<SalesTransactionType>^ SalesTransactionTypes {
    IEnumerable<SalesTransactionType>^ get ();
    void set (IEnumerable<SalesTransactionType>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

