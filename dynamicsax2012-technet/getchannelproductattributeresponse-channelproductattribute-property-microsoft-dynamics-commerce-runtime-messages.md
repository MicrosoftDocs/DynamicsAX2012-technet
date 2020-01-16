---
title: GetChannelProductAttributeResponse.ChannelProductAttribute Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelProductAttribute Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributeResponse.ChannelProductAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelproductattributeresponse.channelproductattribute(v=AX.60)
ms:contentKeyID: 49831725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProductAttributeResponse.ChannelProductAttribute
dev_langs:
- CSharp
- C++
- VB
---

# ChannelProductAttribute Property

Gets the channel product attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelProductAttribute As AttributeProduct
    Get
    Private Set
'Usage
Dim instance As GetChannelProductAttributeResponse
Dim value As AttributeProduct

value = instance.ChannelProductAttribute
```

``` csharp
[DataMemberAttribute]
public AttributeProduct ChannelProductAttribute { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property AttributeProduct^ ChannelProductAttribute {
    AttributeProduct^ get ();
    private: void set (AttributeProduct^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeProduct](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetChannelProductAttributeResponse Class](getchannelproductattributeresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

