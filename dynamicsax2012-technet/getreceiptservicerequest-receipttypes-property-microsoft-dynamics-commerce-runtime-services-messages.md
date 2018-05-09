---
title: GetReceiptServiceRequest.ReceiptTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReceiptTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.ReceiptTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.receipttypes(v=AX.60)
ms:contentKeyID: 62212261
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.ReceiptTypes
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTypes Property

Gets the receipt types that are to be printed/emailed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ReceiptTypes As ReadOnlyCollection(Of ReceiptType)
    Get
    Private Set
'Usage
Dim instance As GetReceiptServiceRequest
Dim value As ReadOnlyCollection(Of ReceiptType)

value = instance.ReceiptTypes
```

``` csharp
public ReadOnlyCollection<ReceiptType> ReceiptTypes { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ReceiptType>^ ReceiptTypes {
    ReadOnlyCollection<ReceiptType>^ get ();
    private: void set (ReadOnlyCollection<ReceiptType>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

