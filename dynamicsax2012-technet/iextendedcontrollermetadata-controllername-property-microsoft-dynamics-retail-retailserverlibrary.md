---
title: IExtendedControllerMetadata.ControllerName Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ControllerName Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.IExtendedControllerMetadata.ControllerName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.iextendedcontrollermetadata.controllername(v=AX.60)
ms:contentKeyID: 62203053
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.IExtendedControllerMetadata.ControllerName
dev_langs:
- CSharp
- C++
- VB
---

# ControllerName Property

Gets the name of the service.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ControllerName As String
    Get
'Usage
Dim instance As IExtendedControllerMetadata
Dim value As String

value = instance.ControllerName
```

``` csharp
string ControllerName { get; }
```

``` c++
property String^ ControllerName {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The name of the service.  

## See Also

#### Reference

[IExtendedControllerMetadata Interface](iextendedcontrollermetadata-interface-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

