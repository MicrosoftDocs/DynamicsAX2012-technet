---
title: GetItemAvailabilitiesRequest.MaxWarehousesPerItem Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: MaxWarehousesPerItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesRequest.MaxWarehousesPerItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemavailabilitiesrequest.maxwarehousesperitem(v=AX.60)
ms:contentKeyID: 49823523
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesRequest.MaxWarehousesPerItem
dev_langs:
- CSharp
- C++
- VB
---

# MaxWarehousesPerItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum number of warehouses per item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MaxWarehousesPerItem As Integer
    Get
    Set
'Usage
Dim instance As GetItemAvailabilitiesRequest
Dim value As Integer

value = instance.MaxWarehousesPerItem

instance.MaxWarehousesPerItem = value
```

``` csharp
[DataMemberAttribute]
public int MaxWarehousesPerItem { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int MaxWarehousesPerItem {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The maximum number of warehouses per item.  

## See Also

#### Reference

[GetItemAvailabilitiesRequest Class](getitemavailabilitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

