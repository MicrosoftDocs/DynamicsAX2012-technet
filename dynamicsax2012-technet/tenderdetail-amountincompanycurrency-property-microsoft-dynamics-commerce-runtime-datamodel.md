---
title: TenderDetail.AmountInCompanyCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountInCompanyCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.AmountInCompanyCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.amountincompanycurrency(v=AX.60)
ms:contentKeyID: 65322137
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.AmountInCompanyCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AmountInCompanyCurrency Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("AMOUNTMST")> _
Public Property AmountInCompanyCurrency As Decimal
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As Decimal

value = instance.AmountInCompanyCurrency

instance.AmountInCompanyCurrency = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("AMOUNTMST")]
public decimal AmountInCompanyCurrency { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"AMOUNTMST")]
public:
property Decimal AmountInCompanyCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

