---
title: RichMediaHelper.PopulateCustomerMediaInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PopulateCustomerMediaInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateCustomerMediaInformation(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.richmediahelper.populatecustomermediainformation(v=AX.60)
ms:contentKeyID: 65322169
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateCustomerMediaInformation
dev_langs:
- CSharp
- C++
- VB
---

# PopulateCustomerMediaInformation Method

Populates the customer media information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateCustomerMediaInformation ( _
    accountNumber As String, _
    mediaBlob As String, _
    defaultValue As String _
) As RichMediaLocations
'Usage
Dim accountNumber As String
Dim mediaBlob As String
Dim defaultValue As String
Dim returnValue As RichMediaLocations

returnValue = RichMediaHelper.PopulateCustomerMediaInformation(accountNumber, _
    mediaBlob, defaultValue)
```

``` csharp
public static RichMediaLocations PopulateCustomerMediaInformation(
    string accountNumber,
    string mediaBlob,
    string defaultValue
)
```

``` c++
public:
static RichMediaLocations^ PopulateCustomerMediaInformation(
    String^ accountNumber, 
    String^ mediaBlob, 
    String^ defaultValue
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - mediaBlob  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
RichMediaLocations object.  

## See Also

#### Reference

[RichMediaHelper Class](richmediahelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

