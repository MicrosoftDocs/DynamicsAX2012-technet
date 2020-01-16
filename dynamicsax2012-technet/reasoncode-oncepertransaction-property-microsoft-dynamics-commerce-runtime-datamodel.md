---
title: ReasonCode.OncePerTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OncePerTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.OncePerTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.oncepertransaction(v=AX.60)
ms:contentKeyID: 62210845
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.OncePerTransaction
dev_langs:
- CSharp
- C++
- VB
---

# OncePerTransaction Property

Gets a value indicating whether once per transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ONCEPERTRANSACTION")> _
<DataMemberAttribute> _
Public Property OncePerTransaction As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Boolean

value = instance.OncePerTransaction
```

``` csharp
[ColumnAttribute("ONCEPERTRANSACTION")]
[DataMemberAttribute]
public bool OncePerTransaction { get; internal set; }
```

``` c++
[ColumnAttribute(L"ONCEPERTRANSACTION")]
[DataMemberAttribute]
public:
property bool OncePerTransaction {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if once per transaction; otherwise, false.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

