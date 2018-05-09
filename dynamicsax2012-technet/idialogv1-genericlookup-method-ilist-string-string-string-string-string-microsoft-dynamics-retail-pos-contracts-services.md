---
title: IDialogV1.GenericLookup Method (IList, String, String, String, String, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GenericLookup Method (IList, String, String, String, String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.GenericLookup(System.Collections.IList,System.String,System.String,System.String,System.String@,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.genericlookup(v=AX.60)
ms:contentKeyID: 47343953
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenericLookup Method (IList, String, String, String, String, String)

Shows a list of class instances.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GenericLookup ( _
    dataTable As IList, _
    displayPropertyName As String, _
    displayColumnCaption As String, _
    returnPropertyName As String, _
    <OutAttribute> ByRef returnPropertyValue As String, _
    defaultValue As String _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim dataTable As IList
Dim displayPropertyName As String
Dim displayColumnCaption As String
Dim returnPropertyName As String
Dim returnPropertyValue As String
Dim defaultValue As String
Dim returnValue As DialogResult

returnValue = instance.GenericLookup(dataTable, _
    displayPropertyName, displayColumnCaption, _
    returnPropertyName, returnPropertyValue, _
    defaultValue)
```

``` csharp
DialogResult GenericLookup(
    IList dataTable,
    string displayPropertyName,
    string displayColumnCaption,
    string returnPropertyName,
    out string returnPropertyValue,
    string defaultValue
)
```

``` c++
DialogResult GenericLookup(
    IList^ dataTable, 
    String^ displayPropertyName, 
    String^ displayColumnCaption, 
    String^ returnPropertyName, 
    [OutAttribute] String^% returnPropertyValue, 
    String^ defaultValue
)
```

#### Parameters

  - dataTable  
    Type: [System.Collections.IList](https://technet.microsoft.com/en-us/library/30ft6hw7\(v=ax.60\))  

<!-- end list -->

  - displayPropertyName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - displayColumnCaption  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - returnPropertyName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - returnPropertyValue  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/en-us/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[GenericLookup Overload](idialogv1-genericlookup-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

