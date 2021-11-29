---
title: TokenizedPaymentCard.IsSwipe Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSwipe Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard.IsSwipe
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tokenizedpaymentcard.isswipe(v=AX.60)
ms:contentKeyID: 65320416
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard.IsSwipe
dev_langs:
- CSharp
- C++
- VB
---

# IsSwipe Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether IsSwipe is true or false.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overrides Property IsSwipe As Boolean
    Get
    Set
'Usage
Dim instance As TokenizedPaymentCard
Dim value As Boolean

value = instance.IsSwipe

instance.IsSwipe = value
```

``` csharp
[DataMemberAttribute]
public override bool IsSwipe { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property bool IsSwipe {
    bool get () override;
    void set (bool value) override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if this instance is swipe; otherwise, false.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/2asft85a(v=ax.60)">InvalidOperationException</a></td>
<td><p>A tokenized payment card is always entered manually.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[TokenizedPaymentCard Class](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

