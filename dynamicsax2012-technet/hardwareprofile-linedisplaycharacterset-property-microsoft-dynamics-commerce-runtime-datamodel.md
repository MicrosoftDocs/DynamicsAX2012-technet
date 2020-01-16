---
title: HardwareProfile.LineDisplayCharacterSet Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayCharacterSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayCharacterSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaycharacterset(v=AX.60)
ms:contentKeyID: 62211614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayCharacterSet
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayCharacterSet Property

Gets or sets the display character set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYCHARACTERSET")> _
Public Property LineDisplayCharacterSet As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.LineDisplayCharacterSet

instance.LineDisplayCharacterSet = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYCHARACTERSET")]
public int LineDisplayCharacterSet { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYCHARACTERSET")]
public:
property int LineDisplayCharacterSet {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The numeric value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

