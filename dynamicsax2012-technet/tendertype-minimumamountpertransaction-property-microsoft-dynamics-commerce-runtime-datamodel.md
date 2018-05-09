---
title: TenderType.MinimumAmountPerTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumAmountPerTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumAmountPerTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.minimumamountpertransaction(v=AX.60)
ms:contentKeyID: 62210783
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumAmountPerTransaction
dev_langs:
- CSharp
- C++
- VB
---

# MinimumAmountPerTransaction Property

Gets or sets the minimum amount per transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MINIMUMAMOUNTPERTRANSACTION")> _
Public Property MinimumAmountPerTransaction As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MinimumAmountPerTransaction

instance.MinimumAmountPerTransaction = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MINIMUMAMOUNTPERTRANSACTION")]
public decimal MinimumAmountPerTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MINIMUMAMOUNTPERTRANSACTION")]
public:
property Decimal MinimumAmountPerTransaction {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

