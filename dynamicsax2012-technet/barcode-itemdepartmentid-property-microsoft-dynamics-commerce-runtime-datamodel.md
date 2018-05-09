---
title: Barcode.ItemDepartmentId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemDepartmentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ItemDepartmentId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.itemdepartmentid(v=AX.60)
ms:contentKeyID: 62211496
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ItemDepartmentId
dev_langs:
- CSharp
- C++
- VB
---

# ItemDepartmentId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemDepartmentId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.ItemDepartmentId

instance.ItemDepartmentId = value
```

``` csharp
[DataMemberAttribute]
public string ItemDepartmentId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ItemDepartmentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

