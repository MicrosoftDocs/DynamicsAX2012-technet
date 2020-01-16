---
title: GetProductKitDataResponse.KitDefinitions Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: KitDefinitions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitDefinitions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdataresponse.kitdefinitions(v=AX.60)
ms:contentKeyID: 65319323
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitDefinitions
dev_langs:
- CSharp
- C++
- VB
---

# KitDefinitions Property

Gets the kit definition collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property KitDefinitions As ReadOnlyCollection(Of KitDefinition)
    Get
    Private Set
'Usage
Dim instance As GetProductKitDataResponse
Dim value As ReadOnlyCollection(Of KitDefinition)

value = instance.KitDefinitions
```

``` csharp
public ReadOnlyCollection<KitDefinition> KitDefinitions { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<KitDefinition^>^ KitDefinitions {
    ReadOnlyCollection<KitDefinition^>^ get ();
    private: void set (ReadOnlyCollection<KitDefinition^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductKitDataResponse Class](getproductkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

