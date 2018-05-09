---
title: ItemBarcode.Blocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Blocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.Blocked
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.blocked(v=AX.60)
ms:contentKeyID: 62212050
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.Blocked
dev_langs:
- CSharp
- C++
- VB
---

# Blocked Property

Gets the Item barcode status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BLOCKED")> _
<DataMemberAttribute> _
Public Property Blocked As Integer
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As Integer

value = instance.Blocked
```

``` csharp
[ColumnAttribute("BLOCKED")]
[DataMemberAttribute]
public int Blocked { get; internal set; }
```

``` c++
[ColumnAttribute(L"BLOCKED")]
[DataMemberAttribute]
public:
property int Blocked {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

