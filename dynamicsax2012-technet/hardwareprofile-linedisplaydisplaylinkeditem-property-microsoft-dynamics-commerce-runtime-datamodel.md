---
title: HardwareProfile.LineDisplayDisplayLinkedItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDisplayLinkedItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDisplayLinkedItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydisplaylinkeditem(v=AX.60)
ms:contentKeyID: 62210642
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDisplayLinkedItem
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDisplayLinkedItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether display linked items value is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYLINKEDITEM")> _
Public Property LineDisplayDisplayLinkedItem As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.LineDisplayDisplayLinkedItem

instance.LineDisplayDisplayLinkedItem = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYLINKEDITEM")]
public bool LineDisplayDisplayLinkedItem { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYLINKEDITEM")]
public:
property bool LineDisplayDisplayLinkedItem {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if display linked items is set; otherwise, false.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

