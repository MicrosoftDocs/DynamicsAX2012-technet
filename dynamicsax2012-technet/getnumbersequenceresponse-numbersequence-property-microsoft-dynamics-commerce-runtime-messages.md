---
title: GetNumberSequenceResponse.NumberSequence Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NumberSequence Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetNumberSequenceResponse.NumberSequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getnumbersequenceresponse.numbersequence(v=AX.60)
ms:contentKeyID: 65318922
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetNumberSequenceResponse.NumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequence Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequence As ReadOnlyCollection(Of NumberSequenceSeedData)
    Get
    Private Set
'Usage
Dim instance As GetNumberSequenceResponse
Dim value As ReadOnlyCollection(Of NumberSequenceSeedData)

value = instance.NumberSequence
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<NumberSequenceSeedData> NumberSequence { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<NumberSequenceSeedData^>^ NumberSequence {
    ReadOnlyCollection<NumberSequenceSeedData^>^ get ();
    private: void set (ReadOnlyCollection<NumberSequenceSeedData^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[NumberSequenceSeedData](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetNumberSequenceResponse Class](getnumbersequenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

