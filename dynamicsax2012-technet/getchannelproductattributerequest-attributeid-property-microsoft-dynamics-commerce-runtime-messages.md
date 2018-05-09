---
title: GetChannelProductAttributeRequest.AttributeId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AttributeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributeRequest.AttributeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelproductattributerequest.attributeid(v=AX.60)
ms:contentKeyID: 49828492
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributeRequest.AttributeId
dev_langs:
- CSharp
- C++
- VB
---

# AttributeId Property

Gets or sets the attribute identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AttributeId As Long
    Get
    Set
'Usage
Dim instance As GetChannelProductAttributeRequest
Dim value As Long

value = instance.AttributeId

instance.AttributeId = value
```

``` csharp
[DataMemberAttribute]
public long AttributeId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long AttributeId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The attribute identifier.  

## See Also

#### Reference

[GetChannelProductAttributeRequest Class](getchannelproductattributerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

