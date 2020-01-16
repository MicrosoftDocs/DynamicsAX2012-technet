---
title: GetTaxOverridesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetTaxOverridesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettaxoverridesdatarequest.gettaxoverridesdatarequest(v=AX.60)
ms:contentKeyID: 65321709
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTaxOverridesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxOverridesDataRequest Constructor

Initializes a new instance of the [GetTaxOverridesDataRequest](gettaxoverridesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    overrideBy As TaxOverrideBy _
)
'Usage
Dim channelId As Long
Dim overrideBy As TaxOverrideBy

Dim instance As New GetTaxOverridesDataRequest(channelId, _
    overrideBy)
```

``` csharp
public GetTaxOverridesDataRequest(
    long channelId,
    TaxOverrideBy overrideBy
)
```

``` c++
public:
GetTaxOverridesDataRequest(
    long long channelId, 
    TaxOverrideBy overrideBy
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - overrideBy  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetTaxOverridesDataRequest Class](gettaxoverridesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

