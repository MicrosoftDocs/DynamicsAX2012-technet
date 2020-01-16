---
title: TenderLineBase.AmountInCompanyCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountInCompanyCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.AmountInCompanyCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.amountincompanycurrency(v=AX.60)
ms:contentKeyID: 62202726
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.AmountInCompanyCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AmountInCompanyCurrency Property

Gets or sets the amount in company currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AMOUNTINCOMPANYCURRENCY")> _
Public Property AmountInCompanyCurrency As Decimal
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Decimal

value = instance.AmountInCompanyCurrency

instance.AmountInCompanyCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AMOUNTINCOMPANYCURRENCY")]
public decimal AmountInCompanyCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AMOUNTINCOMPANYCURRENCY")]
public:
property Decimal AmountInCompanyCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The amount converted to company currency.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

