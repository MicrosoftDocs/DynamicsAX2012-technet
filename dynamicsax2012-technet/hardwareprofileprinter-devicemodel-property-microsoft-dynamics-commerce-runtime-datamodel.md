---
title: HardwareProfilePrinter.DeviceModel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceModel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceModel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicemodel(v=AX.60)
ms:contentKeyID: 62210105
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceModel
dev_langs:
- CSharp
- C++
- VB
---

# DeviceModel Property

Gets or sets the printer device model.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERMODELVALUE")> _
Public Property DeviceModel As String
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As String

value = instance.DeviceModel

instance.DeviceModel = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERMODELVALUE")]
public string DeviceModel { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERMODELVALUE")]
public:
property String^ DeviceModel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The model string.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

