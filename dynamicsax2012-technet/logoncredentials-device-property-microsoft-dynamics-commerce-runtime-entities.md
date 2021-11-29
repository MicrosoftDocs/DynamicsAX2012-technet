---
title: LogonCredentials.Device Property  (Microsoft.Dynamics.Commerce.Runtime.Entities)
TOCTitle: Device Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Device
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.entities.logoncredentials.device(v=AX.60)
ms:contentKeyID: 65323069
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Device
dev_langs:
- CSharp
- C++
- VB
---

# Device Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the device information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Entities](microsoft-dynamics-commerce-runtime-entities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Device As Device
    Get
    Set
'Usage
Dim instance As LogonCredentials
Dim value As Device

value = instance.Device

instance.Device = value
```

``` csharp
[DataMemberAttribute]
public Device Device { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Device^ Device {
    Device^ get ();
    void set (Device^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LogonCredentials Class](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)

[Microsoft.Dynamics.Commerce.Runtime.Entities Namespace](microsoft-dynamics-commerce-runtime-entities-namespace.md)

