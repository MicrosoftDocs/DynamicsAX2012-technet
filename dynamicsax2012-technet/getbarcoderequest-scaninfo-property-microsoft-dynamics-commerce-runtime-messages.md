---
title: GetBarcodeRequest.ScanInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ScanInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeRequest.ScanInfo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getbarcoderequest.scaninfo(v=AX.60)
ms:contentKeyID: 62205960
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetBarcodeRequest.ScanInfo
dev_langs:
- CSharp
- C++
- VB
---

# ScanInfo Property

Gets the barcode scan information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property ScanInfo As ScanInfo
    Get
    Private Set
'Usage
Dim instance As GetBarcodeRequest
Dim value As ScanInfo

value = instance.ScanInfo
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ScanInfo ScanInfo { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ScanInfo^ ScanInfo {
    ScanInfo^ get ();
    private: void set (ScanInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo](scaninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ScanInfo](scaninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetBarcodeRequest Class](getbarcoderequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

