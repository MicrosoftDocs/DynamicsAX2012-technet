---
title: ShiftsController.Use Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Use Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.Use(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.use(v=AX.60)
ms:contentKeyID: 62202239
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.Use
dev_langs:
- CSharp
- C++
- VB
---

# Use Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Uses an existing shift.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Function Use ( _
    terminalId As String, _
    shiftId As Long _
) As Shift
'Usage
Dim instance As ShiftsController
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As Shift

returnValue = instance.Use(terminalId, _
    shiftId)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public Shift Use(
    string terminalId,
    long shiftId
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
Shift^ Use(
    String^ terminalId, 
    long long shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: Shift  
The shift object.  

## Remarks

We do not have an AX operation mapping to this API, so permission checks are done at workflow level.

## See Also

#### Reference

[ShiftsController Class](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

