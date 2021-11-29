---
title: GetNumberSequenceSeedDataTransactionServiceResponse.NumberSequenceSeedData Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NumberSequenceSeedData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNumberSequenceSeedDataTransactionServiceResponse.NumberSequenceSeedData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnumbersequenceseeddatatransactionserviceresponse.numbersequenceseeddata(v=AX.60)
ms:contentKeyID: 65320853
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNumberSequenceSeedDataTransactionServiceResponse.NumberSequenceSeedData
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceSeedData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequenceSeedData As IEnumerable(Of NumberSequenceSeedData)
    Get
    Private Set
'Usage
Dim instance As GetNumberSequenceSeedDataTransactionServiceResponse
Dim value As IEnumerable(Of NumberSequenceSeedData)

value = instance.NumberSequenceSeedData
```

``` csharp
[DataMemberAttribute]
public IEnumerable<NumberSequenceSeedData> NumberSequenceSeedData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<NumberSequenceSeedData^>^ NumberSequenceSeedData {
    IEnumerable<NumberSequenceSeedData^>^ get ();
    private: void set (IEnumerable<NumberSequenceSeedData^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[NumberSequenceSeedData](numbersequenceseeddata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetNumberSequenceSeedDataTransactionServiceResponse Class](getnumbersequenceseeddatatransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

