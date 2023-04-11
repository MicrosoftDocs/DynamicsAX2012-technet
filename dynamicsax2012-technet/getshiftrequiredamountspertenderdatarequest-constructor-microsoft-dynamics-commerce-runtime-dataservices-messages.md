---
title: GetShiftRequiredAmountsPerTenderDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetShiftRequiredAmountsPerTenderDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshiftrequiredamountspertenderdatarequest.getshiftrequiredamountspertenderdatarequest(v=AX.60)
ms:contentKeyID: 65319927
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShiftRequiredAmountsPerTenderDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShiftRequiredAmountsPerTenderDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShiftRequiredAmountsPerTenderDataRequest](getshiftrequiredamountspertenderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    terminalId As String, _
    shiftId As String _
)
'Usage
Dim terminalId As String
Dim shiftId As String

Dim instance As New GetShiftRequiredAmountsPerTenderDataRequest(terminalId, _
    shiftId)
```

``` csharp
public GetShiftRequiredAmountsPerTenderDataRequest(
    string terminalId,
    string shiftId
)
```

``` c++
public:
GetShiftRequiredAmountsPerTenderDataRequest(
    String^ terminalId, 
    String^ shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetShiftRequiredAmountsPerTenderDataRequest Class](getshiftrequiredamountspertenderdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

