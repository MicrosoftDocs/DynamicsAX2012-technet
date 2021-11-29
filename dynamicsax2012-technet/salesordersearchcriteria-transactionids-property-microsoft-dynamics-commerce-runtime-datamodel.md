---
title: SalesOrderSearchCriteria.TransactionIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.TransactionIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.transactionids(v=AX.60)
ms:contentKeyID: 62215121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.TransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# TransactionIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionIds As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As IEnumerable(Of String)

value = instance.TransactionIds

instance.TransactionIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> TransactionIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ TransactionIds {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

