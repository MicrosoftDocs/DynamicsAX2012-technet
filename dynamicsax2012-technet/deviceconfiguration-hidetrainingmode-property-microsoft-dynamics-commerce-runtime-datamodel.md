---
title: DeviceConfiguration.HideTrainingMode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HideTrainingMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.HideTrainingMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.hidetrainingmode(v=AX.60)
ms:contentKeyID: 62214253
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.HideTrainingMode
dev_langs:
- CSharp
- C++
- VB
---

# HideTrainingMode Property

Gets or sets a value indicating whether hide training mode is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("HIDETRAININGMODE")> _
<DataMemberAttribute> _
Public Property HideTrainingMode As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.HideTrainingMode

instance.HideTrainingMode = value
```

``` csharp
[ColumnAttribute("HIDETRAININGMODE")]
[DataMemberAttribute]
public bool HideTrainingMode { get; set; }
```

``` c++
[ColumnAttribute(L"HIDETRAININGMODE")]
[DataMemberAttribute]
public:
property bool HideTrainingMode {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value true if hide training mode is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

