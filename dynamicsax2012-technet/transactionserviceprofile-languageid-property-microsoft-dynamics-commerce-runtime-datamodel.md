---
title: TransactionServiceProfile.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.LanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.languageid(v=AX.60)
ms:contentKeyID: 62213904
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property

Gets the transaction service language identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TSLANGUAGEID")> _
Public ReadOnly Property LanguageId As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.LanguageId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TSLANGUAGEID")]
public string LanguageId { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TSLANGUAGEID")]
public:
property String^ LanguageId {
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

