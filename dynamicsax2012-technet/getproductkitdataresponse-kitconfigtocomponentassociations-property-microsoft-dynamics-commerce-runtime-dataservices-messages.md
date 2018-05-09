---
title: GetProductKitDataResponse.KitConfigToComponentAssociations Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: KitConfigToComponentAssociations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitConfigToComponentAssociations
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdataresponse.kitconfigtocomponentassociations(v=AX.60)
ms:contentKeyID: 65320848
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.KitConfigToComponentAssociations
dev_langs:
- CSharp
- C++
- VB
---

# KitConfigToComponentAssociations Property

Gets the kit configuration to component associations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property KitConfigToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation)
    Get
    Private Set
'Usage
Dim instance As GetProductKitDataResponse
Dim value As ReadOnlyCollection(Of KitConfigToComponentAssociation)

value = instance.KitConfigToComponentAssociations
```

``` csharp
public ReadOnlyCollection<KitConfigToComponentAssociation> KitConfigToComponentAssociations { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<KitConfigToComponentAssociation^>^ KitConfigToComponentAssociations {
    ReadOnlyCollection<KitConfigToComponentAssociation^>^ get ();
    private: void set (ReadOnlyCollection<KitConfigToComponentAssociation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[KitConfigToComponentAssociation](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductKitDataResponse Class](getproductkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

