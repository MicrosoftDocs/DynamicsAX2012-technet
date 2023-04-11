---
title: ReasonCode.MaximumLength Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumLength Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MaximumLength
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.maximumlength(v=AX.60)
ms:contentKeyID: 62210841
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.MaximumLength
dev_langs:
- CSharp
- C++
- VB
---

# MaximumLength Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum length.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MAXIMUMLENGTH")> _
Public Property MaximumLength As Integer
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Integer

value = instance.MaximumLength
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MAXIMUMLENGTH")]
public int MaximumLength { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MAXIMUMLENGTH")]
public:
property int MaximumLength {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The maximum length.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

