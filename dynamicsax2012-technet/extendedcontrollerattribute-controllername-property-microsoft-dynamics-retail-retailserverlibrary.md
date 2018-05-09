---
title: ExtendedControllerAttribute.ControllerName Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ControllerName Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerAttribute.ControllerName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.extendedcontrollerattribute.controllername(v=AX.60)
ms:contentKeyID: 62201767
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerAttribute.ControllerName
dev_langs:
- CSharp
- C++
- VB
---

# ControllerName Property

Gets the name of the controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Property ControllerName As String
    Get
    Private Set
'Usage
Dim instance As ExtendedControllerAttribute
Dim value As String

value = instance.ControllerName
```

``` csharp
public string ControllerName { get; private set; }
```

``` c++
public:
virtual property String^ ControllerName {
    String^ get () sealed;
    private: void set (String^ value) sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The name of the controller.  

#### Implements

[IExtendedControllerMetadata.ControllerName](iextendedcontrollermetadata-controllername-property-microsoft-dynamics-retail-retailserverlibrary.md)  

## See Also

#### Reference

[ExtendedControllerAttribute Class](extendedcontrollerattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

