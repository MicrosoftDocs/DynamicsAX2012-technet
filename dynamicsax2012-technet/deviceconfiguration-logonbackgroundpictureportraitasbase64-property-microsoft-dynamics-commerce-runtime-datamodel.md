---
title: DeviceConfiguration.LogOnBackgroundPicturePortraitAsBase64 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnBackgroundPicturePortraitAsBase64 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPicturePortraitAsBase64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.logonbackgroundpictureportraitasbase64(v=AX.60)
ms:contentKeyID: 65322361
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPicturePortraitAsBase64
dev_langs:
- CSharp
- C++
- VB
---

# LogOnBackgroundPicturePortraitAsBase64 Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOGONBACKGROUNDPICTUREPORTRAIT")> _
Public Property LogOnBackgroundPicturePortraitAsBase64 As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.LogOnBackgroundPicturePortraitAsBase64

instance.LogOnBackgroundPicturePortraitAsBase64 = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOGONBACKGROUNDPICTUREPORTRAIT")]
public string LogOnBackgroundPicturePortraitAsBase64 { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOGONBACKGROUNDPICTUREPORTRAIT")]
public:
property String^ LogOnBackgroundPicturePortraitAsBase64 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

