---
title: HardwareProfile.DualDisplayActive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DualDisplayActive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayActive
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.dualdisplayactive(v=AX.60)
ms:contentKeyID: 62206131
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayActive
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplayActive Property

Gets or sets a value indicating whether dual display is active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DUALDISPLAY")> _
Public Property DualDisplayActive As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.DualDisplayActive

instance.DualDisplayActive = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DUALDISPLAY")]
public bool DualDisplayActive { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DUALDISPLAY")]
public:
property bool DualDisplayActive {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if dual display is active; otherwise, false.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

