---
title: GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForShift Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequenceValueForShift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForShift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlatestnumbersequencedataserviceresponse.numbersequencevalueforshift(v=AX.60)
ms:contentKeyID: 65319881
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForShift
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceValueForShift Property

Gets the number sequence value for shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequenceValueForShift As Shift
    Get
    Private Set
'Usage
Dim instance As GetLatestNumberSequenceDataServiceResponse
Dim value As Shift

value = instance.NumberSequenceValueForShift
```

``` csharp
[DataMemberAttribute]
public Shift NumberSequenceValueForShift { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Shift^ NumberSequenceValueForShift {
    Shift^ get ();
    private: void set (Shift^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetLatestNumberSequenceDataServiceResponse Class](getlatestnumbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

