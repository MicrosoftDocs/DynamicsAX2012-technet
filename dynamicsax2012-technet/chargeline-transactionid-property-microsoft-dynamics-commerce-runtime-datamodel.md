---
title: ChargeLine.TransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.transactionid(v=AX.60)
ms:contentKeyID: 62210009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TRANSACTIONID")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("TRANSACTIONID")> _
Public Property TransactionId As String
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As String

value = instance.TransactionId

instance.TransactionId = value
```

``` csharp
[ColumnAttribute("TRANSACTIONID")]
[DataMemberAttribute]
[ReadOnlyAttribute("TRANSACTIONID")]
public string TransactionId { get; set; }
```

``` c++
[ColumnAttribute(L"TRANSACTIONID")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"TRANSACTIONID")]
public:
property String^ TransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

