---
title: GetEmailReceiptServiceResponse.Receipts Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Receipts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceResponse.Receipts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptserviceresponse.receipts(v=AX.60)
ms:contentKeyID: 62214800
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceResponse.Receipts
dev_langs:
- CSharp
- C++
- VB
---

# Receipts Property

Gets the receipts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Receipts As ReadOnlyCollection(Of Receipt)
    Get
    Private Set
'Usage
Dim instance As GetEmailReceiptServiceResponse
Dim value As ReadOnlyCollection(Of Receipt)

value = instance.Receipts
```

``` csharp
public ReadOnlyCollection<Receipt> Receipts { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<Receipt^>^ Receipts {
    ReadOnlyCollection<Receipt^>^ get ();
    private: void set (ReadOnlyCollection<Receipt^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Receipt](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetEmailReceiptServiceResponse Class](getemailreceiptserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

