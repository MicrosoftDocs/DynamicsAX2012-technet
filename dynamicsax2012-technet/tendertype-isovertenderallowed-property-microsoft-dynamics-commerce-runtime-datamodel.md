---
title: TenderType.IsOvertenderAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsOvertenderAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.IsOvertenderAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.isovertenderallowed(v=AX.60)
ms:contentKeyID: 62204259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.IsOvertenderAllowed
dev_langs:
- CSharp
- C++
- VB
---

# IsOvertenderAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether overtendering is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWOVERTENDER")> _
<DataMemberAttribute> _
Public Property IsOvertenderAllowed As Boolean
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Boolean

value = instance.IsOvertenderAllowed

instance.IsOvertenderAllowed = value
```

``` csharp
[ColumnAttribute("ALLOWOVERTENDER")]
[DataMemberAttribute]
public bool IsOvertenderAllowed { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWOVERTENDER")]
[DataMemberAttribute]
public:
property bool IsOvertenderAllowed {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true then overtender is allowed; otherwise, false.  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

