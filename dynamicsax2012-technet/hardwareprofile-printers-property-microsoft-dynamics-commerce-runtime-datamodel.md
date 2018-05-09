---
title: HardwareProfile.Printers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Printers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.Printers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.printers(v=AX.60)
ms:contentKeyID: 62204987
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.Printers
dev_langs:
- CSharp
- C++
- VB
---

# Printers Property

Gets the printers in the hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Printers As ReadOnlyCollection(Of HardwareProfilePrinter)
    Get
    Private Set
'Usage
Dim instance As HardwareProfile
Dim value As ReadOnlyCollection(Of HardwareProfilePrinter)

value = instance.Printers
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<HardwareProfilePrinter> Printers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<HardwareProfilePrinter^>^ Printers {
    ReadOnlyCollection<HardwareProfilePrinter^>^ get ();
    private: void set (ReadOnlyCollection<HardwareProfilePrinter^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[HardwareProfilePrinter](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of printers associated with the hardware profile.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

