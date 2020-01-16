---
title: TenderType.MaxRecount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaxRecount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaxRecount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maxrecount(v=AX.60)
ms:contentKeyID: 65320833
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaxRecount
dev_langs:
- CSharp
- C++
- VB
---

# MaxRecount Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("MAXRECOUNT")> _
Public Property MaxRecount As Integer
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.MaxRecount

instance.MaxRecount = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("MAXRECOUNT")]
public int MaxRecount { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"MAXRECOUNT")]
public:
property int MaxRecount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

