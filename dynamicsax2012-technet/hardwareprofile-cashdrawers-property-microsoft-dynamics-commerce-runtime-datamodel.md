---
title: HardwareProfile.CashDrawers Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CashDrawers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.CashDrawers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.cashdrawers(v=AX.60)
ms:contentKeyID: 62209131
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.CashDrawers
dev_langs:
- CSharp
- C++
- VB
---

# CashDrawers Property

Gets the cash drawers in the hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CashDrawers As ReadOnlyCollection(Of HardwareProfileCashDrawer)
    Get
    Private Set
'Usage
Dim instance As HardwareProfile
Dim value As ReadOnlyCollection(Of HardwareProfileCashDrawer)

value = instance.CashDrawers
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<HardwareProfileCashDrawer> CashDrawers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<HardwareProfileCashDrawer^>^ CashDrawers {
    ReadOnlyCollection<HardwareProfileCashDrawer^>^ get ();
    private: void set (ReadOnlyCollection<HardwareProfileCashDrawer^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileCashDrawer](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of cash drawers associated with the hardware profile.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

