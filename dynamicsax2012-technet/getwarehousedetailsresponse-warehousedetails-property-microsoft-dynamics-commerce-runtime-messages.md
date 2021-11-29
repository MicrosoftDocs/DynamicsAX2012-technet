---
title: GetWarehouseDetailsResponse.WarehouseDetails Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: WarehouseDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsResponse.WarehouseDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getwarehousedetailsresponse.warehousedetails(v=AX.60)
ms:contentKeyID: 62210466
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsResponse.WarehouseDetails
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item dimensions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WarehouseDetails As ReadOnlyCollection(Of WarehouseDetails)
    Get
    Private Set
'Usage
Dim instance As GetWarehouseDetailsResponse
Dim value As ReadOnlyCollection(Of WarehouseDetails)

value = instance.WarehouseDetails
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<WarehouseDetails> WarehouseDetails { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<WarehouseDetails^>^ WarehouseDetails {
    ReadOnlyCollection<WarehouseDetails^>^ get ();
    private: void set (ReadOnlyCollection<WarehouseDetails^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[WarehouseDetails](warehousedetails-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetWarehouseDetailsResponse Class](getwarehousedetailsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

