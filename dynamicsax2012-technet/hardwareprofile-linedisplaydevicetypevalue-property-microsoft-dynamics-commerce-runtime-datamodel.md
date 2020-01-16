---
title: HardwareProfile.LineDisplayDeviceTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDeviceTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydevicetypevalue(v=AX.60)
ms:contentKeyID: 62209293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDeviceTypeValue Property

Gets or sets the value of the line display device type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDisplayDeviceTypeValue As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.LineDisplayDeviceTypeValue

instance.LineDisplayDeviceTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int LineDisplayDeviceTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int LineDisplayDeviceTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

