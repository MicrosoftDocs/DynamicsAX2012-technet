---
title: ShiftsController.GetXReport Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetXReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetXReport(System.String,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.getxreport(v=AX.60)
ms:contentKeyID: 62203824
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetXReport
dev_langs:
- CSharp
- C++
- VB
---

# GetXReport Method

Gets receipt for X report.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PrintX)> _
<HttpPostAttribute> _
Public Overridable Function GetXReport ( _
    terminalId As String, _
    shiftId As Long _
) As Receipt
'Usage
Dim instance As ShiftsController
Dim terminalId As String
Dim shiftId As Long
Dim returnValue As Receipt

returnValue = instance.GetXReport(terminalId, _
    shiftId)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PrintX)]
[HttpPostAttribute]
public virtual Receipt GetXReport(
    string terminalId,
    long shiftId
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PrintX)]
[HttpPostAttribute]
public:
virtual Receipt^ GetXReport(
    String^ terminalId, 
    long long shiftId
)
```

#### Parameters

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shiftId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: Receipt  
The receipt object.  

## See Also

#### Reference

[ShiftsController Class](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

