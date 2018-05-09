---
title: GetStoreProductAvailabilityRequest.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.VariantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.variantid(v=AX.60)
ms:contentKeyID: 62212717
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property

Gets or sets the variantid identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantId As String
    Get
    Set
'Usage
Dim instance As GetStoreProductAvailabilityRequest
Dim value As String

value = instance.VariantId

instance.VariantId = value
```

``` csharp
[DataMemberAttribute]
public string VariantId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ VariantId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

