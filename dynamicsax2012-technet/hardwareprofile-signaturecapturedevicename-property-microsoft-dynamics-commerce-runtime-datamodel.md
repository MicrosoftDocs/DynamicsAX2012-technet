---
title: HardwareProfile.SignatureCaptureDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureCaptureDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.signaturecapturedevicename(v=AX.60)
ms:contentKeyID: 62209819
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureDeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the signature capture device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SIGCAPDEVICENAME")> _
Public Property SignatureCaptureDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.SignatureCaptureDeviceName

instance.SignatureCaptureDeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SIGCAPDEVICENAME")]
public string SignatureCaptureDeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SIGCAPDEVICENAME")]
public:
property String^ SignatureCaptureDeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

