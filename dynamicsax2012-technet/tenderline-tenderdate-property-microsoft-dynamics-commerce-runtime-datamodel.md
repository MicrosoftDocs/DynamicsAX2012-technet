---
title: TenderLine.TenderDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.TenderDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderline.tenderdate(v=AX.60)
ms:contentKeyID: 62210853
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.TenderDate
dev_langs:
- CSharp
- C++
- VB
---

# TenderDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets tender date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TENDERDATE")> _
<DataMemberAttribute> _
Public Property TenderDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As TenderLine
Dim value As Nullable(Of DateTimeOffset)

value = instance.TenderDate

instance.TenderDate = value
```

``` csharp
[ColumnAttribute("TENDERDATE")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> TenderDate { get; set; }
```

``` c++
[ColumnAttribute(L"TENDERDATE")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> TenderDate {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[TenderLine Class](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

