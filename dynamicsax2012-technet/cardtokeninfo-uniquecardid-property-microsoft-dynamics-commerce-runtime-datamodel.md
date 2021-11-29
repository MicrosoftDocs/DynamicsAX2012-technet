---
title: CardTokenInfo.UniqueCardId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UniqueCardId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.UniqueCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtokeninfo.uniquecardid(v=AX.60)
ms:contentKeyID: 65323193
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.UniqueCardId
dev_langs:
- CSharp
- C++
- VB
---

# UniqueCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the unique payment card identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UniqueCardId As String
    Get
    Set
'Usage
Dim instance As CardTokenInfo
Dim value As String

value = instance.UniqueCardId

instance.UniqueCardId = value
```

``` csharp
[DataMemberAttribute]
public string UniqueCardId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UniqueCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTokenInfo Class](cardtokeninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

