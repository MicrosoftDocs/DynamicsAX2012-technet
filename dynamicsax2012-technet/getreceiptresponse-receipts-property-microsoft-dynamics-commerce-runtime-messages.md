---
title: GetReceiptResponse.Receipts Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Receipts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptResponse.Receipts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreceiptresponse.receipts(v=AX.60)
ms:contentKeyID: 62205965
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptResponse.Receipts
dev_langs:
- CSharp
- C++
- VB
---

# Receipts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of receipts for a transaction. Each element returns a receipt type that is to be printed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Receipts As ReadOnlyCollection(Of Receipt)
    Get
    Private Set
'Usage
Dim instance As GetReceiptResponse
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

[GetReceiptResponse Class](getreceiptresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

