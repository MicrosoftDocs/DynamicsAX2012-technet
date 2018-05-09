---
title: PropertyInfoExtensions.AdjustToChannelTimeZone Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AdjustToChannelTimeZone Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.PropertyInfoExtensions.AdjustToChannelTimeZone(System.Reflection.PropertyInfo,System.Object,System.Collections.Generic.List{Microsoft.Dynamics.Commerce.Runtime.DataModel.TimeZoneInterval},Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.propertyinfoextensions.adjusttochanneltimezone(v=AX.60)
ms:contentKeyID: 65320581
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.PropertyInfoExtensions.AdjustToChannelTimeZone
dev_langs:
- CSharp
- C++
- VB
---

# AdjustToChannelTimeZone Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub AdjustToChannelTimeZone ( _
    property As PropertyInfo, _
    value As Object, _
    channelTimeZones As List(Of TimeZoneInterval), _
    typeCache As TypeCache _
)
'Usage
Dim property As PropertyInfo
Dim value As Object
Dim channelTimeZones As List(Of TimeZoneInterval)
Dim typeCache As TypeCache

property.AdjustToChannelTimeZone(value, _
    channelTimeZones, typeCache)
```

``` csharp
public static void AdjustToChannelTimeZone(
    this PropertyInfo property,
    Object value,
    List<TimeZoneInterval> channelTimeZones,
    TypeCache typeCache
)
```

``` c++
[ExtensionAttribute]
public:
static void AdjustToChannelTimeZone(
    PropertyInfo^ property, 
    Object^ value, 
    List<TimeZoneInterval^>^ channelTimeZones, 
    TypeCache^ typeCache
)
```

#### Parameters

  - property  
    Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\))  

<!-- end list -->

  - value  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  

<!-- end list -->

  - channelTimeZones  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/en-us/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - typeCache  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[PropertyInfoExtensions Class](propertyinfoextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

