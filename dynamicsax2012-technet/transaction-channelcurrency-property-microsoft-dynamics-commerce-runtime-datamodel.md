---
title: Transaction.ChannelCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.ChannelCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transaction.channelcurrency(v=AX.60)
ms:contentKeyID: 65319361
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Transaction.ChannelCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CURRENCY")> _
Public Property ChannelCurrency As String
    Get
    Set
'Usage
Dim instance As Transaction
Dim value As String

value = instance.ChannelCurrency

instance.ChannelCurrency = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CURRENCY")]
public string ChannelCurrency { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CURRENCY")]
public:
property String^ ChannelCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Transaction Class](transaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

