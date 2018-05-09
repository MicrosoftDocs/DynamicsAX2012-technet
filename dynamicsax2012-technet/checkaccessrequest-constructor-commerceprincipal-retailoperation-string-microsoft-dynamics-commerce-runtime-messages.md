---
title: CheckAccessRequest Constructor (CommercePrincipal, RetailOperation, String ) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CheckAccessRequest Constructor (CommercePrincipal, RetailOperation, String )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,System.String[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.checkaccessrequest(v=AX.60)
ms:contentKeyID: 62207898
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CheckAccessRequest Constructor (CommercePrincipal, RetailOperation, String )

Initializes a new instance of the [CheckAccessRequest](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commercePrincipal As CommercePrincipal, _
    retailOperation As RetailOperation, _
    allowedRoles As String() _
)
'Usage
Dim commercePrincipal As CommercePrincipal
Dim retailOperation As RetailOperation
Dim allowedRoles As String()

Dim instance As New CheckAccessRequest(commercePrincipal, _
    retailOperation, allowedRoles)
```

``` csharp
public CheckAccessRequest(
    CommercePrincipal commercePrincipal,
    RetailOperation retailOperation,
    string[] allowedRoles
)
```

``` c++
public:
CheckAccessRequest(
    CommercePrincipal^ commercePrincipal, 
    RetailOperation retailOperation, 
    array<String^>^ allowedRoles
)
```

#### Parameters

  - commercePrincipal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - retailOperation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - allowedRoles  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[CheckAccessRequest Overload](checkaccessrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

