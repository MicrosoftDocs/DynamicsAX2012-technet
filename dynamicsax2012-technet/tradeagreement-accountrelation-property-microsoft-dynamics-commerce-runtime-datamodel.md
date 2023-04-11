---
title: TradeAgreement.AccountRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.AccountRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.accountrelation(v=AX.60)
ms:contentKeyID: 49833807
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.AccountRelation
dev_langs:
- CSharp
- C++
- VB
---

# AccountRelation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer configuration identifier (could be customer identifier, price group identifier, or empty).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ACCOUNTRELATION")> _
Public Property AccountRelation As String
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As String

value = instance.AccountRelation
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ACCOUNTRELATION")]
public string AccountRelation { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ACCOUNTRELATION")]
public:
property String^ AccountRelation {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

