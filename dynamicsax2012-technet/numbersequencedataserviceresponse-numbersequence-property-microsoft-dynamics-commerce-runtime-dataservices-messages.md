---
title: NumberSequenceDataServiceResponse.NumberSequence Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequence Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceResponse.NumberSequence
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.numbersequencedataserviceresponse.numbersequence(v=AX.60)
ms:contentKeyID: 65316599
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceResponse.NumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequence Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number sequence.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property NumberSequence As Long
    Get
    Private Set
'Usage
Dim instance As NumberSequenceDataServiceResponse
Dim value As Long

value = instance.NumberSequence
```

``` csharp
public long NumberSequence { get; private set; }
```

``` c++
public:
property long long NumberSequence {
    long long get ();
    private: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[NumberSequenceDataServiceResponse Class](numbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

