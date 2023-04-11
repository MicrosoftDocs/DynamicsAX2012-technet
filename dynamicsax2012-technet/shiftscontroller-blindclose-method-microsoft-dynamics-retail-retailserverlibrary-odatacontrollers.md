---
title: ShiftsController.BlindClose Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: BlindClose Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.BlindClose(System.String,System.Int64,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.blindclose(v=AX.60)
ms:contentKeyID: 62201782
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.BlindClose
dev_langs:
- CSharp
- C++
- VB
---

# BlindClose Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Blind closes a shift.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.BlindCloseShift)> _
Public Overridable Function BlindClose ( _
    terminalId As String, _
    shiftId As Long, _
    parameters As ODataActionParameters _
) As Shift
'Usage
Dim instance As ShiftsController
Dim terminalId As String
Dim shiftId As Long
Dim parameters As ODataActionParameters
Dim returnValue As Shift

returnValue = instance.BlindClose(terminalId, _
    shiftId, parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.BlindCloseShift)]
public virtual Shift BlindClose(
    string terminalId,
    long shiftId,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::BlindCloseShift)]
public:
virtual Shift^ BlindClose(
    String^ terminalId, 
    long long shiftId, 
    ODataActionParameters^ parameters
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Shift  
The shift object.  

## See Also

#### Reference

[ShiftsController Class](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

