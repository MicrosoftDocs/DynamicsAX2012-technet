---
title: HardwareProfile.ScaleManualInputAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleManualInputAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleManualInputAllowed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scalemanualinputallowed(v=AX.60)
ms:contentKeyID: 62209757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleManualInputAllowed
dev_langs:
- CSharp
- C++
- VB
---

# ScaleManualInputAllowed Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether manual input on scale is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MANUALINPUTALLOWED")> _
Public Property ScaleManualInputAllowed As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.ScaleManualInputAllowed

instance.ScaleManualInputAllowed = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MANUALINPUTALLOWED")]
public bool ScaleManualInputAllowed { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MANUALINPUTALLOWED")]
public:
property bool ScaleManualInputAllowed {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if manual input on scale is allowed; otherwise, false.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

