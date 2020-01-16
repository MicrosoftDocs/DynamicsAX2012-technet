---
title: CommerceEntityDataExtensions.CreateDataRow Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreateDataRow Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.CreateDataRow(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentitydataextensions.createdatarow(v=AX.60)
ms:contentKeyID: 65321982
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataExtensions.CreateDataRow
dev_langs:
- CSharp
- C++
- VB
---

# CreateDataRow Method

Loads the entity property bag into the data row, given the table schema.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function CreateDataRow ( _
    entity As CommerceEntity, _
    table As DataTable _
) As DataRow
'Usage
Dim entity As CommerceEntity
Dim table As DataTable
Dim returnValue As DataRow

returnValue = entity.CreateDataRow(table)
```

``` csharp
public static DataRow CreateDataRow(
    this CommerceEntity entity,
    DataTable table
)
```

``` c++
[ExtensionAttribute]
public:
static DataRow^ CreateDataRow(
    CommerceEntity^ entity, 
    DataTable^ table
)
```

#### Parameters

  - entity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - table  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The created data row.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[CommerceEntityDataExtensions Class](commerceentitydataextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

