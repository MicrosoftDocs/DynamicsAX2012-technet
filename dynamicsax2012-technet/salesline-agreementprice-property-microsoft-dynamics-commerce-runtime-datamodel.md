---
title: SalesLine.AgreementPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AgreementPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AgreementPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.agreementprice(v=AX.60)
ms:contentKeyID: 62207935
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.AgreementPrice
dev_langs:
- CSharp
- C++
- VB
---

# AgreementPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the trade agreement price of the item on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AGREEMENTPRICE")> _
<DataMemberAttribute> _
Public Property AgreementPrice As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.AgreementPrice

instance.AgreementPrice = value
```

``` csharp
[ColumnAttribute("AGREEMENTPRICE")]
[DataMemberAttribute]
public decimal AgreementPrice { get; set; }
```

``` c++
[ColumnAttribute(L"AGREEMENTPRICE")]
[DataMemberAttribute]
public:
property Decimal AgreementPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

