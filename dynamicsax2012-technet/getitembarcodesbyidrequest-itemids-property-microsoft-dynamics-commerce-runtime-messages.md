---
title: GetItemBarcodesByIdRequest.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest.ItemIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitembarcodesbyidrequest.itemids(v=AX.60)
ms:contentKeyID: 62207943
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemBarcodesByIdRequest.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property

Gets the collection of item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetItemBarcodesByIdRequest
Dim value As IEnumerable(Of String)

value = instance.ItemIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ItemIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ItemIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetItemBarcodesByIdRequest Class](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

