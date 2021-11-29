---
title: TenderType.MaximumAmountPerTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumAmountPerTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumAmountPerTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maximumamountpertransaction(v=AX.60)
ms:contentKeyID: 62204597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumAmountPerTransaction
dev_langs:
- CSharp
- C++
- VB
---

# MaximumAmountPerTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum amount per transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMAMOUNTPERTRANSACTION")> _
<DataMemberAttribute> _
Public Property MaximumAmountPerTransaction As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MaximumAmountPerTransaction

instance.MaximumAmountPerTransaction = value
```

``` csharp
[ColumnAttribute("MAXIMUMAMOUNTPERTRANSACTION")]
[DataMemberAttribute]
public decimal MaximumAmountPerTransaction { get; set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMAMOUNTPERTRANSACTION")]
[DataMemberAttribute]
public:
property Decimal MaximumAmountPerTransaction {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

