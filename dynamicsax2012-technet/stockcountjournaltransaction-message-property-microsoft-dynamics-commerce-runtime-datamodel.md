---
title: StockCountJournalTransaction.Message Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.message(v=AX.60)
ms:contentKeyID: 62212885
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MESSAGE")> _
Public Property Message As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.Message

instance.Message = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MESSAGE")]
public string Message { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MESSAGE")]
public:
property String^ Message {
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

