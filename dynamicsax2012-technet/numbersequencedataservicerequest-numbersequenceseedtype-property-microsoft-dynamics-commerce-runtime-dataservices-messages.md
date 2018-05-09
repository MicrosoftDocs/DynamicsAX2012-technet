---
title: NumberSequenceDataServiceRequest.NumberSequenceSeedType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequenceSeedType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.NumberSequenceSeedType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.numbersequencedataservicerequest.numbersequenceseedtype(v=AX.60)
ms:contentKeyID: 65316764
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.NumberSequenceSeedType
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceSeedType Property

Gets the number sequence seed type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequenceSeedType As NumberSequenceSeedType
    Get
    Private Set
'Usage
Dim instance As NumberSequenceDataServiceRequest
Dim value As NumberSequenceSeedType

value = instance.NumberSequenceSeedType
```

``` csharp
[DataMemberAttribute]
public NumberSequenceSeedType NumberSequenceSeedType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property NumberSequenceSeedType NumberSequenceSeedType {
    NumberSequenceSeedType get ();
    private: void set (NumberSequenceSeedType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[NumberSequenceDataServiceRequest Class](numbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

