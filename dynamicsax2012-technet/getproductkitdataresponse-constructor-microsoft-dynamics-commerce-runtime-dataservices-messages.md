---
title: GetProductKitDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductKitDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductkitdataresponse.getproductkitdataresponse(v=AX.60)
ms:contentKeyID: 65315690
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductKitDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductKitDataResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductKitDataResponse](getproductkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitDefinitions As ReadOnlyCollection(Of KitDefinition), _
    kitComponentAndSubstituteList As ReadOnlyCollection(Of KitComponent), _
    kitConfigToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation) _
)
'Usage
Dim kitDefinitions As ReadOnlyCollection(Of KitDefinition)
Dim kitComponentAndSubstituteList As ReadOnlyCollection(Of KitComponent)
Dim kitConfigToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation)

Dim instance As New GetProductKitDataResponse(kitDefinitions, _
    kitComponentAndSubstituteList, _
    kitConfigToComponentAssociations)
```

``` csharp
public GetProductKitDataResponse(
    ReadOnlyCollection<KitDefinition> kitDefinitions,
    ReadOnlyCollection<KitComponent> kitComponentAndSubstituteList,
    ReadOnlyCollection<KitConfigToComponentAssociation> kitConfigToComponentAssociations
)
```

``` c++
public:
GetProductKitDataResponse(
    ReadOnlyCollection<KitDefinition^>^ kitDefinitions, 
    ReadOnlyCollection<KitComponent^>^ kitComponentAndSubstituteList, 
    ReadOnlyCollection<KitConfigToComponentAssociation^>^ kitConfigToComponentAssociations
)
```

#### Parameters

  - kitDefinitions  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - kitComponentAndSubstituteList  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - kitConfigToComponentAssociations  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitConfigToComponentAssociation](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductKitDataResponse Class](getproductkitdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

