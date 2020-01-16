---
title: GetParentKitDataRequest.MasterProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: MasterProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataRequest.MasterProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getparentkitdatarequest.masterproductids(v=AX.60)
ms:contentKeyID: 65315736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetParentKitDataRequest.MasterProductIds
dev_langs:
- CSharp
- C++
- VB
---

# MasterProductIds Property

Gets the collection of the master product identifiers present in the [ProductIds](getparentkitdatarequest-productids-property-microsoft-dynamics-commerce-runtime-dataservices-messages.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property MasterProductIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetParentKitDataRequest
Dim value As IEnumerable(Of Long)

value = instance.MasterProductIds
```

``` csharp
public IEnumerable<long> MasterProductIds { get; private set; }
```

``` c++
public:
property IEnumerable<long long>^ MasterProductIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetParentKitDataRequest Class](getparentkitdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

