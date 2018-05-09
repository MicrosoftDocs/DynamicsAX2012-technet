---
title: IndiaTaxDataManager.GetTaxComponentIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTaxComponentIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetTaxComponentIndia(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.indiataxdatamanager.gettaxcomponentindia(v=AX.60)
ms:contentKeyID: 62203409
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetTaxComponentIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxComponentIndia Method

Gets tax component info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTaxComponentIndia ( _
    taxCode As String _
) As TaxComponentIndia
'Usage
Dim instance As IndiaTaxDataManager
Dim taxCode As String
Dim returnValue As TaxComponentIndia

returnValue = instance.GetTaxComponentIndia(taxCode)
```

``` csharp
public TaxComponentIndia GetTaxComponentIndia(
    string taxCode
)
```

``` c++
public:
TaxComponentIndia^ GetTaxComponentIndia(
    String^ taxCode
)
```

#### Parameters

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxComponentIndia](taxcomponentindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Tax component info.  

## See Also

#### Reference

[IndiaTaxDataManager Class](indiataxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

