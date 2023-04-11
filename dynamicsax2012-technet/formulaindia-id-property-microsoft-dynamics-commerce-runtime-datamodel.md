---
title: FormulaIndia.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.formulaindia.id(v=AX.60)
ms:contentKeyID: 62210372
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FormulaIndia.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets priority for the tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ID")> _
<DataMemberAttribute> _
Public Property Id As Integer
    Get
    Friend Set
'Usage
Dim instance As FormulaIndia
Dim value As Integer

value = instance.Id
```

``` csharp
[ColumnAttribute("ID")]
[DataMemberAttribute]
public int Id { get; internal set; }
```

``` c++
[ColumnAttribute(L"ID")]
[DataMemberAttribute]
public:
property int Id {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[FormulaIndia Class](formulaindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

