---
title: TransactionServiceProfile.IsSecurityDisabled Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSecurityDisabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.IsSecurityDisabled
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.issecuritydisabled(v=AX.60)
ms:contentKeyID: 62213553
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.IsSecurityDisabled
dev_langs:
- CSharp
- C++
- VB
---

# IsSecurityDisabled Property

Gets a value indicating whether to have transaction service security disabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSSECURITYOFF")> _
Public ReadOnly Property IsSecurityDisabled As Boolean
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As Boolean

value = instance.IsSecurityDisabled
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSSECURITYOFF")]
public bool IsSecurityDisabled { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSSECURITYOFF")]
public:
property bool IsSecurityDisabled {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

