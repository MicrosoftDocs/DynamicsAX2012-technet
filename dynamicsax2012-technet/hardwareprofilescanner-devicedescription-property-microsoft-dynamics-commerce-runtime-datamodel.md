---
title: HardwareProfileScanner.DeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileScanner.DeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilescanner.devicedescription(v=AX.60)
ms:contentKeyID: 62208464
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileScanner.DeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# DeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the scanner device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SCANNERDESCRIPTIONVALUE")> _
Public Property DeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfileScanner
Dim value As String

value = instance.DeviceDescription

instance.DeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SCANNERDESCRIPTIONVALUE")]
public string DeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SCANNERDESCRIPTIONVALUE")]
public:
property String^ DeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description string.  

## See Also

#### Reference

[HardwareProfileScanner Class](hardwareprofilescanner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

