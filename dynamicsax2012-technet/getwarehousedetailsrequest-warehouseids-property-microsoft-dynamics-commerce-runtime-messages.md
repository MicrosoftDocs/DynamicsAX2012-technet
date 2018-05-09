---
title: GetWarehouseDetailsRequest.WarehouseIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: WarehouseIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsRequest.WarehouseIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getwarehousedetailsrequest.warehouseids(v=AX.60)
ms:contentKeyID: 62208450
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsRequest.WarehouseIds
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseIds Property

Gets or sets the list of warehouse identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WarehouseIds As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As GetWarehouseDetailsRequest
Dim value As IEnumerable(Of String)

value = instance.WarehouseIds

instance.WarehouseIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> WarehouseIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ WarehouseIds {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetWarehouseDetailsRequest Class](getwarehousedetailsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

