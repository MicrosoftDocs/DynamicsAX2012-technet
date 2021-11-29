---
title: LineDeliveryPreference.OnDeserializing Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OnDeserializing Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.OnDeserializing(System.Runtime.Serialization.StreamingContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreference.ondeserializing(v=AX.60)
ms:contentKeyID: 65322815
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.OnDeserializing
dev_langs:
- CSharp
- C++
- VB
---

# OnDeserializing Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The deserialization handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<OnDeserializingAttribute> _
Public Sub OnDeserializing ( _
    context As StreamingContext _
)
'Usage
Dim instance As LineDeliveryPreference
Dim context As StreamingContext

instance.OnDeserializing(context)
```

``` csharp
[OnDeserializingAttribute]
public void OnDeserializing(
    StreamingContext context
)
```

``` c++
[OnDeserializingAttribute]
public:
void OnDeserializing(
    StreamingContext context
)
```

#### Parameters

  - context  
    Type: [System.Runtime.Serialization.StreamingContext](https://technet.microsoft.com/library/t16abws5\(v=ax.60\))  

## See Also

#### Reference

[LineDeliveryPreference Class](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

