---
title: SalesOrderSearchCriteria.StartDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.StartDateTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.startdatetime(v=AX.60)
ms:contentKeyID: 62212121
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.StartDateTime
dev_langs:
- CSharp
- C++
- VB
---

# StartDateTime Property

Gets or sets the start time for filtering.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredToBeUtcAttribute(True)> _
<DataMemberAttribute> _
Public Property StartDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As Nullable(Of DateTimeOffset)

value = instance.StartDateTime

instance.StartDateTime = value
```

``` csharp
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
public Nullable<DateTimeOffset> StartDateTime { get; set; }
```

``` c++
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> StartDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

