---
title: TenderLineBase.IsChangeLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsChangeLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsChangeLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.ischangeline(v=AX.60)
ms:contentKeyID: 62201789
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.IsChangeLine
dev_langs:
- CSharp
- C++
- VB
---

# IsChangeLine Property

Gets or sets a value indicating whether this instance is a change line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISCHANGELINE")> _
<DataMemberAttribute> _
Public Property IsChangeLine As Boolean
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Boolean

value = instance.IsChangeLine

instance.IsChangeLine = value
```

``` csharp
[ColumnAttribute("ISCHANGELINE")]
[DataMemberAttribute]
public bool IsChangeLine { get; set; }
```

``` c++
[ColumnAttribute(L"ISCHANGELINE")]
[DataMemberAttribute]
public:
property bool IsChangeLine {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true this tender line is a change line; otherwise, false.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

