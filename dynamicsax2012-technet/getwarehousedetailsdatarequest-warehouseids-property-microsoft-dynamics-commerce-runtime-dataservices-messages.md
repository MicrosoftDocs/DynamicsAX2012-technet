---
title: GetWarehouseDetailsDataRequest.WarehouseIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: WarehouseIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest.WarehouseIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getwarehousedetailsdatarequest.warehouseids(v=AX.60)
ms:contentKeyID: 65320092
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetWarehouseDetailsDataRequest.WarehouseIds
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseIds Property

Gets the warehouse ids.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WarehouseIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetWarehouseDetailsDataRequest
Dim value As IEnumerable(Of String)

value = instance.WarehouseIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> WarehouseIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ WarehouseIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
The warehouse ids.  

## See Also

#### Reference

[GetWarehouseDetailsDataRequest Class](getwarehousedetailsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

