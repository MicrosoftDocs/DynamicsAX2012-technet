---
title: ReasonCodeRequirement.TableRefType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TableRefType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.TableRefType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncoderequirement.tablereftype(v=AX.60)
ms:contentKeyID: 62214858
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement.TableRefType
dev_langs:
- CSharp
- C++
- VB
---

# TableRefType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the table ref type of the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TABLEREFERENCETYPE")> _
Public Property TableRefType As ReasonCodeTableRefType
    Get
    Friend Set
'Usage
Dim instance As ReasonCodeRequirement
Dim value As ReasonCodeTableRefType

value = instance.TableRefType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TABLEREFERENCETYPE")]
public ReasonCodeTableRefType TableRefType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TABLEREFERENCETYPE")]
public:
property ReasonCodeTableRefType TableRefType {
    ReasonCodeTableRefType get ();
    internal: void set (ReasonCodeTableRefType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeTableRefType](reasoncodetablereftype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the table.  

## See Also

#### Reference

[ReasonCodeRequirement Class](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

