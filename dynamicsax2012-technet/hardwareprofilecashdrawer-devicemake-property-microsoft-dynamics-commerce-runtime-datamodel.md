---
title: HardwareProfileCashDrawer.DeviceMake Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceMake Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceMake
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.devicemake(v=AX.60)
ms:contentKeyID: 62212528
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceMake
dev_langs:
- CSharp
- C++
- VB
---

# DeviceMake Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash drawer device make.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DRAWERMAKEVALUE")> _
<DataMemberAttribute> _
Public Property DeviceMake As String
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As String

value = instance.DeviceMake

instance.DeviceMake = value
```

``` csharp
[ColumnAttribute("DRAWERMAKEVALUE")]
[DataMemberAttribute]
public string DeviceMake { get; set; }
```

``` c++
[ColumnAttribute(L"DRAWERMAKEVALUE")]
[DataMemberAttribute]
public:
property String^ DeviceMake {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The make string.  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

