---
title: HardwareProfile.SignatureCaptureMake Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureCaptureMake Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureMake
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.signaturecapturemake(v=AX.60)
ms:contentKeyID: 62204509
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureMake
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureMake Property

Gets or sets the signature capture device make.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SIGCAPMAKE")> _
<DataMemberAttribute> _
Public Property SignatureCaptureMake As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.SignatureCaptureMake

instance.SignatureCaptureMake = value
```

``` csharp
[ColumnAttribute("SIGCAPMAKE")]
[DataMemberAttribute]
public string SignatureCaptureMake { get; set; }
```

``` c++
[ColumnAttribute(L"SIGCAPMAKE")]
[DataMemberAttribute]
public:
property String^ SignatureCaptureMake {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The make string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

