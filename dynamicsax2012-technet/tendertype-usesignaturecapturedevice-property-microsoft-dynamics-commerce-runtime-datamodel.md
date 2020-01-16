---
title: TenderType.UseSignatureCaptureDevice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseSignatureCaptureDevice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.UseSignatureCaptureDevice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.usesignaturecapturedevice(v=AX.60)
ms:contentKeyID: 62210319
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.UseSignatureCaptureDevice
dev_langs:
- CSharp
- C++
- VB
---

# UseSignatureCaptureDevice Property

Gets or sets a value indicating whether to use signature capture device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USESIGNATURECAPTUREDEVICE")> _
Public Property UseSignatureCaptureDevice As Boolean
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Boolean

value = instance.UseSignatureCaptureDevice

instance.UseSignatureCaptureDevice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USESIGNATURECAPTUREDEVICE")]
public bool UseSignatureCaptureDevice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USESIGNATURECAPTUREDEVICE")]
public:
property bool UseSignatureCaptureDevice {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

