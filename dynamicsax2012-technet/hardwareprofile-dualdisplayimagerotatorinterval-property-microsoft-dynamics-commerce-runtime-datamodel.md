---
title: HardwareProfile.DualDisplayImageRotatorInterval Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DualDisplayImageRotatorInterval Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayImageRotatorInterval
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.dualdisplayimagerotatorinterval(v=AX.60)
ms:contentKeyID: 62207955
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayImageRotatorInterval
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplayImageRotatorInterval Property

Gets or sets the dual display image rotation interval in seconds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DUALDISPLAYIMAGEINTERVAL")> _
<DataMemberAttribute> _
Public Property DualDisplayImageRotatorInterval As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.DualDisplayImageRotatorInterval

instance.DualDisplayImageRotatorInterval = value
```

``` csharp
[ColumnAttribute("DUALDISPLAYIMAGEINTERVAL")]
[DataMemberAttribute]
public int DualDisplayImageRotatorInterval { get; set; }
```

``` c++
[ColumnAttribute(L"DUALDISPLAYIMAGEINTERVAL")]
[DataMemberAttribute]
public:
property int DualDisplayImageRotatorInterval {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The rotation interval.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

