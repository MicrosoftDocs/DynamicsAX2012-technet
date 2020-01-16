---
title: GetItemAvailabilitiesDataRequest.QueryCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: QueryCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemAvailabilitiesDataRequest.QueryCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemavailabilitiesdatarequest.querycriteria(v=AX.60)
ms:contentKeyID: 65319251
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemAvailabilitiesDataRequest.QueryCriteria
dev_langs:
- CSharp
- C++
- VB
---

# QueryCriteria Property

Gets the collection of item and quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QueryCriteria As ItemAvailabilitiesQueryCriteria
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesDataRequest
Dim value As ItemAvailabilitiesQueryCriteria

value = instance.QueryCriteria
```

``` csharp
[DataMemberAttribute]
public ItemAvailabilitiesQueryCriteria QueryCriteria { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ItemAvailabilitiesQueryCriteria^ QueryCriteria {
    ItemAvailabilitiesQueryCriteria^ get ();
    private: void set (ItemAvailabilitiesQueryCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetItemAvailabilitiesDataRequest Class](getitemavailabilitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

