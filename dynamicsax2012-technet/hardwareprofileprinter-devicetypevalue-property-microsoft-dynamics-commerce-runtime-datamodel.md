---
title: HardwareProfilePrinter.DeviceTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicetypevalue(v=AX.60)
ms:contentKeyID: 62214342
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# DeviceTypeValue Property

Gets or sets the value of the printer device type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceTypeValue As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As Integer

value = instance.DeviceTypeValue

instance.DeviceTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int DeviceTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DeviceTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

