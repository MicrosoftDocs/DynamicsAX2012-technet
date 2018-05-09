---
title: GetHardwareProfileResponse.HardwareProfile Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: HardwareProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetHardwareProfileResponse.HardwareProfile
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.gethardwareprofileresponse.hardwareprofile(v=AX.60)
ms:contentKeyID: 62210125
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetHardwareProfileResponse.HardwareProfile
dev_langs:
- CSharp
- C++
- VB
---

# HardwareProfile Property

Gets the hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HardwareProfile As HardwareProfile
    Get
    Private Set
'Usage
Dim instance As GetHardwareProfileResponse
Dim value As HardwareProfile

value = instance.HardwareProfile
```

``` csharp
[DataMemberAttribute]
public HardwareProfile HardwareProfile { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property HardwareProfile^ HardwareProfile {
    HardwareProfile^ get ();
    private: void set (HardwareProfile^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [HardwareProfile](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetHardwareProfileResponse Class](gethardwareprofileresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

