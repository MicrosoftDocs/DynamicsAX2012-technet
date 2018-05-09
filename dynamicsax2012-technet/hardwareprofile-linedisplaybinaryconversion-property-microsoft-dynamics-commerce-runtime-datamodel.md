---
title: HardwareProfile.LineDisplayBinaryConversion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayBinaryConversion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayBinaryConversion
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaybinaryconversion(v=AX.60)
ms:contentKeyID: 62211698
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayBinaryConversion
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayBinaryConversion Property

Gets or sets a value indicating whether binary conversion value is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYBINCONVERSION")> _
Public Property LineDisplayBinaryConversion As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.LineDisplayBinaryConversion

instance.LineDisplayBinaryConversion = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYBINCONVERSION")]
public bool LineDisplayBinaryConversion { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYBINCONVERSION")]
public:
property bool LineDisplayBinaryConversion {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if binary conversion is set; otherwise, false.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

