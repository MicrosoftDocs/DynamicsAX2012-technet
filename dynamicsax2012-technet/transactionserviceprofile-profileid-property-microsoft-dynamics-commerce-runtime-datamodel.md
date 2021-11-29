---
title: TransactionServiceProfile.ProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.profileid(v=AX.60)
ms:contentKeyID: 62205344
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ProfileId
dev_langs:
- CSharp
- C++
- VB
---

# ProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service profile identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSPROFILEID")> _
Public ReadOnly Property ProfileId As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.ProfileId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSPROFILEID")]
public string ProfileId { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSPROFILEID")]
public:
property String^ ProfileId {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

