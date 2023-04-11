---
title: ApplyInterStateTaxIndia.IsApplyInterStateTaxIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsApplyInterStateTaxIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ApplyInterStateTaxIndia.IsApplyInterStateTaxIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.applyinterstatetaxindia.isapplyinterstatetaxindia(v=AX.60)
ms:contentKeyID: 65320484
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ApplyInterStateTaxIndia.IsApplyInterStateTaxIndia
dev_langs:
- CSharp
- C++
- VB
---

# IsApplyInterStateTaxIndia Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the a sales tax group can be specified for inter-state transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISAPPLYINTERSTATETAX")> _
<DataMemberAttribute> _
Public Property IsApplyInterStateTaxIndia As Boolean
    Get
    Friend Set
'Usage
Dim instance As ApplyInterStateTaxIndia
Dim value As Boolean

value = instance.IsApplyInterStateTaxIndia
```

``` csharp
[ColumnAttribute("ISAPPLYINTERSTATETAX")]
[DataMemberAttribute]
public bool IsApplyInterStateTaxIndia { get; internal set; }
```

``` c++
[ColumnAttribute(L"ISAPPLYINTERSTATETAX")]
[DataMemberAttribute]
public:
property bool IsApplyInterStateTaxIndia {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ApplyInterStateTaxIndia Class](applyinterstatetaxindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

