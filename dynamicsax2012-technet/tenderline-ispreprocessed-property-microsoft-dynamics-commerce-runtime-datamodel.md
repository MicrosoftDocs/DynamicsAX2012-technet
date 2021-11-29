---
title: TenderLine.IsPreProcessed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPreProcessed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.IsPreProcessed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderline.ispreprocessed(v=AX.60)
ms:contentKeyID: 65321121
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.IsPreProcessed
dev_langs:
- CSharp
- C++
- VB
---

# IsPreProcessed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISPREPAYMENTCOLUMN")> _
Public Property IsPreProcessed As Boolean
    Get
    Set
'Usage
Dim instance As TenderLine
Dim value As Boolean

value = instance.IsPreProcessed

instance.IsPreProcessed = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISPREPAYMENTCOLUMN")]
public bool IsPreProcessed { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISPREPAYMENTCOLUMN")]
public:
property bool IsPreProcessed {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[TenderLine Class](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

