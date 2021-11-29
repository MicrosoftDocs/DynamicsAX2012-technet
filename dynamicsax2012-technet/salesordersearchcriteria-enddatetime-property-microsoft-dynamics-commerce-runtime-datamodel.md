---
title: SalesOrderSearchCriteria.EndDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EndDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.EndDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.enddatetime(v=AX.60)
ms:contentKeyID: 62210049
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.EndDateTime
dev_langs:
- CSharp
- C++
- VB
---

# EndDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the end time for filtering.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredToBeUtcAttribute(True)> _
Public Property EndDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As Nullable(Of DateTimeOffset)

value = instance.EndDateTime

instance.EndDateTime = value
```

``` csharp
[DataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public Nullable<DateTimeOffset> EndDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredToBeUtcAttribute(true)]
public:
property Nullable<DateTimeOffset> EndDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

