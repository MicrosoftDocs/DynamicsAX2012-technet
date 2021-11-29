---
title: Barcode.ItemGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ItemGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.itemgroupid(v=AX.60)
ms:contentKeyID: 62211364
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.ItemGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ObsoleteAttribute("This property is no longer supported.")> _
Public Property ItemGroupId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.ItemGroupId

instance.ItemGroupId = value
```

``` csharp
[DataMemberAttribute]
[ObsoleteAttribute("This property is no longer supported.")]
public string ItemGroupId { get; set; }
```

``` c++
[DataMemberAttribute]
[ObsoleteAttribute(L"This property is no longer supported.")]
public:
property String^ ItemGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

