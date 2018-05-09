---
title: ChannelAttribute.ChannelAttributeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelAttributeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttribute.ChannelAttributeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelattribute.channelattributevalue(v=AX.60)
ms:contentKeyID: 49838535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttribute.ChannelAttributeValue
dev_langs:
- CSharp
- C++
- VB
---

# ChannelAttributeValue Property

Gets or sets the channel attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelAttributeValue As AttributeValueBase
    Get
    Set
'Usage
Dim instance As ChannelAttribute
Dim value As AttributeValueBase

value = instance.ChannelAttributeValue

instance.ChannelAttributeValue = value
```

``` csharp
[DataMemberAttribute]
public AttributeValueBase ChannelAttributeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property AttributeValueBase^ ChannelAttributeValue {
    AttributeValueBase^ get ();
    void set (AttributeValueBase^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChannelAttribute Class](channelattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

