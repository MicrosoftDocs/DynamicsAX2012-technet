---
title: GetProductKitDataResponse.KitComponentAndSubstituteList Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: KitComponentAndSubstituteList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitComponentAndSubstituteList
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdataresponse.kitcomponentandsubstitutelist(v=AX.60)
ms:contentKeyID: 65320207
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitComponentAndSubstituteList
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentAndSubstituteList Property

Gets the kit components and substitutes list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property KitComponentAndSubstituteList As ReadOnlyCollection(Of KitComponent)
    Get
    Private Set
'Usage
Dim instance As GetProductKitDataResponse
Dim value As ReadOnlyCollection(Of KitComponent)

value = instance.KitComponentAndSubstituteList
```

``` csharp
public ReadOnlyCollection<KitComponent> KitComponentAndSubstituteList { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<KitComponent^>^ KitComponentAndSubstituteList {
    ReadOnlyCollection<KitComponent^>^ get ();
    private: void set (ReadOnlyCollection<KitComponent^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductKitDataResponse Class](getproductkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

