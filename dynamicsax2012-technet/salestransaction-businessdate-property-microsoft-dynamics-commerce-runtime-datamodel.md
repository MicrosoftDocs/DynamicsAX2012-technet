---
title: SalesTransaction.BusinessDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BusinessDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.BusinessDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.businessdate(v=AX.60)
ms:contentKeyID: 62215179
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.BusinessDate
dev_langs:
- CSharp
- C++
- VB
---

# BusinessDate Property

Gets or sets the business date of transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BUSINESSDATE")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("BUSINESSDATE")> _
Public Property BusinessDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Nullable(Of DateTimeOffset)

value = instance.BusinessDate

instance.BusinessDate = value
```

``` csharp
[ColumnAttribute("BUSINESSDATE")]
[DataMemberAttribute]
[ReadOnlyAttribute("BUSINESSDATE")]
public Nullable<DateTimeOffset> BusinessDate { get; set; }
```

``` c++
[ColumnAttribute(L"BUSINESSDATE")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"BUSINESSDATE")]
public:
property Nullable<DateTimeOffset> BusinessDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

