---
title: TenderLineBase.CardOrAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardOrAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CardOrAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.cardoraccount(v=AX.60)
ms:contentKeyID: 65320179
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.CardOrAccount
dev_langs:
- CSharp
- C++
- VB
---

# CardOrAccount Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDORACCOUNT")> _
<IgnoreDataMemberAttribute> _
Public Property CardOrAccount As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.CardOrAccount

instance.CardOrAccount = value
```

``` csharp
[ColumnAttribute("CARDORACCOUNT")]
[IgnoreDataMemberAttribute]
public string CardOrAccount { get; set; }
```

``` c++
[ColumnAttribute(L"CARDORACCOUNT")]
[IgnoreDataMemberAttribute]
public:
property String^ CardOrAccount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

