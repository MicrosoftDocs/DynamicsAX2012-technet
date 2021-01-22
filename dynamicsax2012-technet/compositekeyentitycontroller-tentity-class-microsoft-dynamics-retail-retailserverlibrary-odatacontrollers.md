---
title: CompositeKeyEntityController(TEntity) Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CompositeKeyEntityController(TEntity) Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn716139(v=AX.60)
ms:contentKeyID: 62202405
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1
dev_langs:
- CSharp
- C++
- VB
---

# CompositeKeyEntityController(TEntity) Class

The composite key entity controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ModelValidatorAttribute> _
<ComVisibleAttribute(False)> _
Public MustInherit Class CompositeKeyEntityController(Of TEntity As Class) _
    Inherits ODataController
'Usage
Dim instance As CompositeKeyEntityController(Of TEntity)
```

``` csharp
[ModelValidatorAttribute]
[ComVisibleAttribute(false)]
public abstract class CompositeKeyEntityController<TEntity> : ODataController
where TEntity : class
```

``` c++
[ModelValidatorAttribute]
[ComVisibleAttribute(false)]
generic<typename TEntity>
where TEntity : ref class
public ref class CompositeKeyEntityController abstract : public ODataController
```

#### Type Parameters

  - TEntity

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController\<TEntity\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

