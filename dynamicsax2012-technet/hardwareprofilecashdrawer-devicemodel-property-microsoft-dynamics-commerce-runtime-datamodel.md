---
title: HardwareProfileCashDrawer.DeviceModel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceModel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.devicemodel(v=AX.60)
ms:contentKeyID: 62205721
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceModel
dev_langs:
- CSharp
- C++
- VB
---

# DeviceModel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash drawer device model.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DRAWERMODELVALUE")> _
<DataMemberAttribute> _
Public Property DeviceModel As String
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As String

value = instance.DeviceModel

instance.DeviceModel = value
```

``` csharp
[ColumnAttribute("DRAWERMODELVALUE")]
[DataMemberAttribute]
public string DeviceModel { get; set; }
```

``` c++
[ColumnAttribute(L"DRAWERMODELVALUE")]
[DataMemberAttribute]
public:
property String^ DeviceModel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The model string.  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

