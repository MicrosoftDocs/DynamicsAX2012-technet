---
title: CardTokenInfo.ServiceAccountId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServiceAccountId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.ServiceAccountId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtokeninfo.serviceaccountid(v=AX.60)
ms:contentKeyID: 65321307
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTokenInfo.ServiceAccountId
dev_langs:
- CSharp
- C++
- VB
---

# ServiceAccountId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the merchant service account identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ServiceAccountId As String
    Get
    Set
'Usage
Dim instance As CardTokenInfo
Dim value As String

value = instance.ServiceAccountId

instance.ServiceAccountId = value
```

``` csharp
[DataMemberAttribute]
public string ServiceAccountId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ServiceAccountId {
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

