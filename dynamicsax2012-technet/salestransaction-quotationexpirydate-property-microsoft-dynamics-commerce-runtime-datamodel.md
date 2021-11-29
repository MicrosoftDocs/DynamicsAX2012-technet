---
title: SalesTransaction.QuotationExpiryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuotationExpiryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.QuotationExpiryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.quotationexpirydate(v=AX.60)
ms:contentKeyID: 62207079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.QuotationExpiryDate
dev_langs:
- CSharp
- C++
- VB
---

# QuotationExpiryDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction comment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXPIRYDATE")> _
Public Property QuotationExpiryDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Nullable(Of DateTimeOffset)

value = instance.QuotationExpiryDate

instance.QuotationExpiryDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXPIRYDATE")]
public Nullable<DateTimeOffset> QuotationExpiryDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXPIRYDATE")]
public:
property Nullable<DateTimeOffset> QuotationExpiryDate {
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

