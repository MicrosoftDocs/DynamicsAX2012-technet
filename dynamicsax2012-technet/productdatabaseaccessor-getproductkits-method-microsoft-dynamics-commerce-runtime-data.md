---
title: ProductDatabaseAccessor.GetProductKits Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductKits Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetProductKits(System.Collections.Generic.IEnumerable{System.Int64},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition}@,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent}@,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.getproductkits(v=AX.60)
ms:contentKeyID: 65315588
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.GetProductKits
dev_langs:
- CSharp
- C++
- VB
---

# GetProductKits Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub GetProductKits ( _
    kitMasterProductIds As IEnumerable(Of Long), _
    <OutAttribute> ByRef kitDefinitions As ReadOnlyCollection(Of KitDefinition), _
    <OutAttribute> ByRef componentAndSubstituteList As ReadOnlyCollection(Of KitComponent), _
    <OutAttribute> ByRef configToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation) _
)
'Usage
Dim instance As ProductDatabaseAccessor
Dim kitMasterProductIds As IEnumerable(Of Long)
Dim kitDefinitions As ReadOnlyCollection(Of KitDefinition)
Dim componentAndSubstituteList As ReadOnlyCollection(Of KitComponent)
Dim configToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation)

instance.GetProductKits(kitMasterProductIds, _
    kitDefinitions, componentAndSubstituteList, _
    configToComponentAssociations)
```

``` csharp
public void GetProductKits(
    IEnumerable<long> kitMasterProductIds,
    out ReadOnlyCollection<KitDefinition> kitDefinitions,
    out ReadOnlyCollection<KitComponent> componentAndSubstituteList,
    out ReadOnlyCollection<KitConfigToComponentAssociation> configToComponentAssociations
)
```

``` c++
public:
void GetProductKits(
    IEnumerable<long long>^ kitMasterProductIds, 
    [OutAttribute] ReadOnlyCollection<KitDefinition^>^% kitDefinitions, 
    [OutAttribute] ReadOnlyCollection<KitComponent^>^% componentAndSubstituteList, 
    [OutAttribute] ReadOnlyCollection<KitConfigToComponentAssociation^>^% configToComponentAssociations
)
```

#### Parameters

  - kitMasterProductIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - kitDefinitions  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - componentAndSubstituteList  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - configToComponentAssociations  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitConfigToComponentAssociation](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

