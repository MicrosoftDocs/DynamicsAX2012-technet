---
title: GetNumberSequenceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetNumberSequenceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNumberSequenceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedData})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getnumbersequenceresponse.getnumbersequenceresponse(v=AX.60)
ms:contentKeyID: 65318597
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetNumberSequenceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetNumberSequenceResponse Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    numberSequenceSeedData As IEnumerable(Of NumberSequenceSeedData) _
)
'Usage
Dim numberSequenceSeedData As IEnumerable(Of NumberSequenceSeedData)

Dim instance As New GetNumberSequenceResponse(numberSequenceSeedData)
```

``` csharp
public GetNumberSequenceResponse(
    IEnumerable<NumberSequenceSeedData> numberSequenceSeedData
)
```

``` c++
public:
GetNumberSequenceResponse(
    IEnumerable<NumberSequenceSeedData^>^ numberSequenceSeedData
)
```

#### Parameters

  - numberSequenceSeedData  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[NumberSequenceSeedData](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetNumberSequenceResponse Class](getnumbersequenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

