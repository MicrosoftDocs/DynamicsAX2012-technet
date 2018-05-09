---
title: ReasonCode.Equals Method (ReasonCode) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (ReasonCode)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.equals(v=AX.60)
ms:contentKeyID: 62210449
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (ReasonCode)

Indicates whether the current object is equal to another object of the same type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As ReasonCode _
) As Boolean
'Usage
Dim instance As ReasonCode
Dim other As ReasonCode
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    ReasonCode other
)
```

``` c++
public:
virtual bool Equals(
    ReasonCode^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if the current object is equal to the other parameter; otherwise, false.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/en-us/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](reasoncode-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

