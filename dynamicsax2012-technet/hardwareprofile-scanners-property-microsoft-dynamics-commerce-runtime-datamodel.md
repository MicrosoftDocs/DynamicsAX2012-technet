---
title: HardwareProfile.Scanners Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Scanners Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.Scanners
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scanners(v=AX.60)
ms:contentKeyID: 62214340
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.Scanners
dev_langs:
- CSharp
- C++
- VB
---

# Scanners Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the scanners in the hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Scanners As ReadOnlyCollection(Of HardwareProfileScanner)
    Get
    Private Set
'Usage
Dim instance As HardwareProfile
Dim value As ReadOnlyCollection(Of HardwareProfileScanner)

value = instance.Scanners
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<HardwareProfileScanner> Scanners { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<HardwareProfileScanner^>^ Scanners {
    ReadOnlyCollection<HardwareProfileScanner^>^ get ();
    private: void set (ReadOnlyCollection<HardwareProfileScanner^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileScanner](hardwareprofilescanner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of scanners associated with the hardware profile.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

