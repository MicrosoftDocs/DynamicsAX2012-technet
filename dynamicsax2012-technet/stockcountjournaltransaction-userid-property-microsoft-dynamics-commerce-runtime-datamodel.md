---
title: StockCountJournalTransaction.UserId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.UserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.userid(v=AX.60)
ms:contentKeyID: 62204783
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.UserId
dev_langs:
- CSharp
- C++
- VB
---

# UserId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the user identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USERID")> _
Public Property UserId As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.UserId

instance.UserId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USERID")]
public string UserId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USERID")]
public:
property String^ UserId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

