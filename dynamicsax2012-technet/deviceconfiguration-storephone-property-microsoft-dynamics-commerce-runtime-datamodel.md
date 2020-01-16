---
title: DeviceConfiguration.StorePhone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StorePhone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StorePhone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.storephone(v=AX.60)
ms:contentKeyID: 62212700
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StorePhone
dev_langs:
- CSharp
- C++
- VB
---

# StorePhone Property

Gets or sets the store phone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PHONE")> _
Public Property StorePhone As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.StorePhone

instance.StorePhone = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PHONE")]
public string StorePhone { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PHONE")]
public:
property String^ StorePhone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the store phone.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

