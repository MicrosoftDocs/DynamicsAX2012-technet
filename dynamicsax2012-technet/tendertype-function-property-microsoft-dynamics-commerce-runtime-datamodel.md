---
title: TenderType.Function Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Function Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.Function
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.function(v=AX.60)
ms:contentKeyID: 62212591
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.Function
dev_langs:
- CSharp
- C++
- VB
---

# Function Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the function.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FUNCTION")> _
Public Property Function As Integer
    Get
    Friend Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.Function
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FUNCTION")]
public int Function { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FUNCTION")]
public:
property int Function {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

