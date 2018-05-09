---
title: DeviceConfiguration.BackgroundPictureAsBase64 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BackgroundPictureAsBase64 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.BackgroundPictureAsBase64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.backgroundpictureasbase64(v=AX.60)
ms:contentKeyID: 62208593
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.BackgroundPictureAsBase64
dev_langs:
- CSharp
- C++
- VB
---

# BackgroundPictureAsBase64 Property

Gets or sets the background picture as base64.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property BackgroundPictureAsBase64 As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.BackgroundPictureAsBase64

instance.BackgroundPictureAsBase64 = value
```

``` csharp
[DataMemberAttribute]
public string BackgroundPictureAsBase64 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ BackgroundPictureAsBase64 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The backgroun picture as base64.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

