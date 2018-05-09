---
title: TenderLineBase.IsVoided Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVoided Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsVoided
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.isvoided(v=AX.60)
ms:contentKeyID: 62212304
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsVoided
dev_langs:
- CSharp
- C++
- VB
---

# IsVoided Property

Gets or sets a value indicating whether the tender line is voided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsVoided As Boolean
    Get
'Usage
Dim instance As TenderLineBase
Dim value As Boolean

value = instance.IsVoided
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsVoided { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsVoided {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

