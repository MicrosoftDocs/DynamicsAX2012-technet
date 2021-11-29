---
title: ReasonCode.MinimumLength Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumLength Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MinimumLength
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.minimumlength(v=AX.60)
ms:contentKeyID: 62213410
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MinimumLength
dev_langs:
- CSharp
- C++
- VB
---

# MinimumLength Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the minimum length.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MINIMUMLENGTH")> _
<DataMemberAttribute> _
Public Property MinimumLength As Integer
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Integer

value = instance.MinimumLength
```

``` csharp
[ColumnAttribute("MINIMUMLENGTH")]
[DataMemberAttribute]
public int MinimumLength { get; internal set; }
```

``` c++
[ColumnAttribute(L"MINIMUMLENGTH")]
[DataMemberAttribute]
public:
property int MinimumLength {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The minimum length.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

