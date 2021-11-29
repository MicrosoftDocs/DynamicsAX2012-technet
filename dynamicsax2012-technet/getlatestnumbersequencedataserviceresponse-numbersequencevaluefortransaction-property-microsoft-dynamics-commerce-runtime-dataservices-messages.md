---
title: GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequenceValueForTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlatestnumbersequencedataserviceresponse.numbersequencevaluefortransaction(v=AX.60)
ms:contentKeyID: 65315470
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForTransaction
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceValueForTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number sequence value for transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequenceValueForTransaction As SalesTransaction
    Get
    Private Set
'Usage
Dim instance As GetLatestNumberSequenceDataServiceResponse
Dim value As SalesTransaction

value = instance.NumberSequenceValueForTransaction
```

``` csharp
[DataMemberAttribute]
public SalesTransaction NumberSequenceValueForTransaction { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesTransaction^ NumberSequenceValueForTransaction {
    SalesTransaction^ get ();
    private: void set (SalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetLatestNumberSequenceDataServiceResponse Class](getlatestnumbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

