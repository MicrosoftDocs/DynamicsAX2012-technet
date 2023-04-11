---
title: TenderLineBase.IsVoidable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsVoidable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsVoidable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.isvoidable(v=AX.60)
ms:contentKeyID: 62210877
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsVoidable
dev_langs:
- CSharp
- C++
- VB
---

# IsVoidable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether tender line can be voided.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISVOIDABLE")> _
Public Property IsVoidable As Boolean
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Boolean

value = instance.IsVoidable

instance.IsVoidable = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISVOIDABLE")]
public bool IsVoidable { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISVOIDABLE")]
public:
property bool IsVoidable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

