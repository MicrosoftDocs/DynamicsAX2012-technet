---
title: ShiftsController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ShiftsController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller(v=AX.60)
ms:contentKeyID: 62203652
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController
dev_langs:
- CSharp
- C++
- VB
---

# ShiftsController Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The shifts controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<ModelValidatorAttribute> _
Public Class ShiftsController _
    Inherits CompositeKeyEntityController(Of Shift)
'Usage
Dim instance As ShiftsController
```

``` csharp
[ComVisibleAttribute(false)]
[ModelValidatorAttribute]
public class ShiftsController : CompositeKeyEntityController<Shift>
```

``` c++
[ComVisibleAttribute(false)]
[ModelValidatorAttribute]
public ref class ShiftsController : public CompositeKeyEntityController<Shift^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController](compositekeyentitycontroller-tentity-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<Shift\>  
        Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

