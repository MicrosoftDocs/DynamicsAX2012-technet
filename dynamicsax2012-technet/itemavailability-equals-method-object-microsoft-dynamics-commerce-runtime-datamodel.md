---
title: ItemAvailability.Equals Method (Object) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (Object)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.Equals(System.Object)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.equals(v=AX.60)
ms:contentKeyID: 62211664
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (Object)

Determines whether the specified [Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\)) is equal to this instance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Equals ( _
    obj As Object _
) As Boolean
'Usage
Dim instance As ItemAvailability
Dim obj As Object
Dim returnValue As Boolean

returnValue = instance.Equals(obj)
```

``` csharp
public override bool Equals(
    Object obj
)
```

``` c++
public:
virtual bool Equals(
    Object^ obj
) override
```

#### Parameters

  - obj  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
If true the specified [Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\)) is equal to this instance; otherwise, false.  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](itemavailability-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

