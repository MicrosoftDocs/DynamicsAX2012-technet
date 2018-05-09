---
title: TaxCode.Calculate Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Calculate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Calculate(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.calculate(v=AX.60)
ms:contentKeyID: 49843065
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Calculate
dev_langs:
- CSharp
- C++
- VB
---

# Calculate Method

Calculates tax for this tax code

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function Calculate ( _
    codes As ReadOnlyCollection(Of TaxCode), _
    calculateBasePrice As Boolean _
) As Decimal
'Usage
Dim instance As TaxCode
Dim codes As ReadOnlyCollection(Of TaxCode)
Dim calculateBasePrice As Boolean
Dim returnValue As Decimal

returnValue = instance.Calculate(codes, _
    calculateBasePrice)
```

``` csharp
public decimal Calculate(
    ReadOnlyCollection<TaxCode> codes,
    bool calculateBasePrice
)
```

``` c++
public:
Decimal Calculate(
    ReadOnlyCollection<TaxCode^>^ codes, 
    bool calculateBasePrice
)
```

#### Parameters

  - codes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  

<!-- end list -->

  - calculateBasePrice  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The calculated tax  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

