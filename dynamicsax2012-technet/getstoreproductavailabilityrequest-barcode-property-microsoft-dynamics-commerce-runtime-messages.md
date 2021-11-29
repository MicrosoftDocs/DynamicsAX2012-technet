---
title: GetStoreProductAvailabilityRequest.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.barcode(v=AX.60)
ms:contentKeyID: 62211531
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcode As String
    Get
    Set
'Usage
Dim instance As GetStoreProductAvailabilityRequest
Dim value As String

value = instance.Barcode

instance.Barcode = value
```

``` csharp
[DataMemberAttribute]
public string Barcode { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Barcode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

