---
title: GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForReceipts Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: NumberSequenceValueForReceipts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForReceipts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlatestnumbersequencedataserviceresponse.numbersequencevalueforreceipts(v=AX.60)
ms:contentKeyID: 65315978
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLatestNumberSequenceDataServiceResponse.NumberSequenceValueForReceipts
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceValueForReceipts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number sequence values for receipt identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberSequenceValueForReceipts As ReadOnlyCollection(Of SalesTransaction)
    Get
    Private Set
'Usage
Dim instance As GetLatestNumberSequenceDataServiceResponse
Dim value As ReadOnlyCollection(Of SalesTransaction)

value = instance.NumberSequenceValueForReceipts
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesTransaction> NumberSequenceValueForReceipts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesTransaction^>^ NumberSequenceValueForReceipts {
    ReadOnlyCollection<SalesTransaction^>^ get ();
    private: void set (ReadOnlyCollection<SalesTransaction^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetLatestNumberSequenceDataServiceResponse Class](getlatestnumbersequencedataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

