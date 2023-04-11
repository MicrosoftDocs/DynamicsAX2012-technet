---
title: HardwareProfile.SignatureCaptureModel Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureCaptureModel Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.signaturecapturemodel(v=AX.60)
ms:contentKeyID: 62203756
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureModel
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureModel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the signature capture device model.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SIGCAPMODEL")> _
Public Property SignatureCaptureModel As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.SignatureCaptureModel

instance.SignatureCaptureModel = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SIGCAPMODEL")]
public string SignatureCaptureModel { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SIGCAPMODEL")]
public:
property String^ SignatureCaptureModel {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The model string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

