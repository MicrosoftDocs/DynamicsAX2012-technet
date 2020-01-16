---
title: ShiftsController.Close Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Close Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.Close(System.String,System.Int64,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.close(v=AX.60)
ms:contentKeyID: 62202494
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.Close
dev_langs:
- CSharp
- C++
- VB
---

# Close Method

Closes the shift for the given terminal.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.CloseShift)> _
<HttpPostAttribute> _
Public Overridable Function Close ( _
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

returnValue = instance.Close(terminalId, _
    shiftId, parameters)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.CloseShift)]
[HttpPostAttribute]
public virtual Shift Close(
    string terminalId,
    long shiftId,
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::CloseShift)]
[HttpPostAttribute]
public:
virtual Shift^ Close(
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

