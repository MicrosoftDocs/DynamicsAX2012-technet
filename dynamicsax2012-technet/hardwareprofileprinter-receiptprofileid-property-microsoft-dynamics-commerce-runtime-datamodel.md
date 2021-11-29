---
title: HardwareProfilePrinter.ReceiptProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.ReceiptProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.receiptprofileid(v=AX.60)
ms:contentKeyID: 62207880
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.ReceiptProfileId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the receipt profile identification.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTERRECEIPTPROFILEIDVALUE")> _
Public Property ReceiptProfileId As String
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As String

value = instance.ReceiptProfileId

instance.ReceiptProfileId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTERRECEIPTPROFILEIDVALUE")]
public string ReceiptProfileId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTERRECEIPTPROFILEIDVALUE")]
public:
property String^ ReceiptProfileId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The receipt profile identification string.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

