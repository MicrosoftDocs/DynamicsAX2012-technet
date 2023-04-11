---
title: HardwareProfile.KeyLockDeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyLockDeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.keylockdevicedescription(v=AX.60)
ms:contentKeyID: 62214083
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# KeyLockDeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the keylock description value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KEYLOCKDESCRIPTION")> _
Public Property KeyLockDeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.KeyLockDeviceDescription

instance.KeyLockDeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KEYLOCKDESCRIPTION")]
public string KeyLockDeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KEYLOCKDESCRIPTION")]
public:
property String^ KeyLockDeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The decription string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

