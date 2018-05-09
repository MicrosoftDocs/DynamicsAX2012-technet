---
title: DeviceConfiguration.MinimumPasswordLength Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumPasswordLength Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MinimumPasswordLength
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.minimumpasswordlength(v=AX.60)
ms:contentKeyID: 62213182
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MinimumPasswordLength
dev_langs:
- CSharp
- C++
- VB
---

# MinimumPasswordLength Property

Gets or sets the minimum password length.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MINIMUMPASSWORDLENGTH")> _
Public Property MinimumPasswordLength As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.MinimumPasswordLength

instance.MinimumPasswordLength = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MINIMUMPASSWORDLENGTH")]
public int MinimumPasswordLength { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MINIMUMPASSWORDLENGTH")]
public:
property int MinimumPasswordLength {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The minimum password length.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

