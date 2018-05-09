---
title: GetItemDeliveryOptionsDataRequest.VariantInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: VariantInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.VariantInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdeliveryoptionsdatarequest.variantinventorydimensionid(v=AX.60)
ms:contentKeyID: 65319440
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.VariantInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# VariantInventoryDimensionId Property

Gets the variant inventory dimension id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantInventoryDimensionId As String
    Get
    Private Set
'Usage
Dim instance As GetItemDeliveryOptionsDataRequest
Dim value As String

value = instance.VariantInventoryDimensionId
```

``` csharp
[DataMemberAttribute]
public string VariantInventoryDimensionId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ VariantInventoryDimensionId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetItemDeliveryOptionsDataRequest Class](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

