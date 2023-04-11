---
title: HardwareProfile.SignatureCaptureDeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureCaptureDeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.signaturecapturedevicedescription(v=AX.60)
ms:contentKeyID: 62212961
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureDeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the signature capture device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SIGCAPDESCRIPTION")> _
Public Property SignatureCaptureDeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.SignatureCaptureDeviceDescription

instance.SignatureCaptureDeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SIGCAPDESCRIPTION")]
public string SignatureCaptureDeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SIGCAPDESCRIPTION")]
public:
property String^ SignatureCaptureDeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

