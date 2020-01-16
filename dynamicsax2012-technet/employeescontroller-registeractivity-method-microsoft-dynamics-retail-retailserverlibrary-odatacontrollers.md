---
title: EmployeesController.RegisterActivity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RegisterActivity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.RegisterActivity(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.registeractivity(v=AX.60)
ms:contentKeyID: 62201827
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.RegisterActivity
dev_langs:
- CSharp
- C++
- VB
---

# RegisterActivity Method

Registers the activity of the employee and returns the date time.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function RegisterActivity ( _
    key As String, _
    parameters As ODataActionParameters _
) As DateTimeOffset
'Usage
Dim instance As EmployeesController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As DateTimeOffset

returnValue = instance.RegisterActivity(key, _
    parameters)
```

``` csharp
[HttpPostAttribute]
public virtual DateTimeOffset RegisterActivity(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual DateTimeOffset RegisterActivity(
    String^ key, 
    ODataActionParameters^ parameters
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns the activity date and time offset currently performed. The [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

