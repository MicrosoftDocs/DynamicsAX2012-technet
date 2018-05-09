---
title: NumberSequenceDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequenceDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.numbersequencedataservicerequest.numbersequencedataservicerequest(v=AX.60)
ms:contentKeyID: 65320980
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceDataServiceRequest Constructor

Initializes a new instance of the [NumberSequenceDataServiceRequest](numbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    numberSequenceType As NumberSequenceSeedType, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim numberSequenceType As NumberSequenceSeedType
Dim storeId As String
Dim terminalId As String

Dim instance As New NumberSequenceDataServiceRequest(numberSequenceType, _
    storeId, terminalId)
```

``` csharp
public NumberSequenceDataServiceRequest(
    NumberSequenceSeedType numberSequenceType,
    string storeId,
    string terminalId
)
```

``` c++
public:
NumberSequenceDataServiceRequest(
    NumberSequenceSeedType numberSequenceType, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - numberSequenceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[NumberSequenceDataServiceRequest Class](numbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

