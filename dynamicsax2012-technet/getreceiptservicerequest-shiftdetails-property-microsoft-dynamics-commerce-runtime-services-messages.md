---
title: GetReceiptServiceRequest.ShiftDetails Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShiftDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.ShiftDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.shiftdetails(v=AX.60)
ms:contentKeyID: 62214821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.ShiftDetails
dev_langs:
- CSharp
- C++
- VB
---

# ShiftDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shift for printing X and Z reports.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftDetails As Shift
    Get
    Set
'Usage
Dim instance As GetReceiptServiceRequest
Dim value As Shift

value = instance.ShiftDetails

instance.ShiftDetails = value
```

``` csharp
[DataMemberAttribute]
public Shift ShiftDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Shift^ ShiftDetails {
    Shift^ get ();
    void set (Shift^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

