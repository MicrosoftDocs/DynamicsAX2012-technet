---
title: Using Data Contracts in X++
TOCTitle: Using Data Contracts in X++
ms:assetid: efaa56a9-4741-45ae-b2ed-b4d6592649d4
ms:mtpsurl: https://technet.microsoft.com/library/Gg848068(v=AX.60)
ms:contentKeyID: 35253295
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Using Data Contracts in X++ 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX supports the use of .NET and X++ types as data contracts for service operation input and return parameters. This enables you to pass complex data types without having to explicitly implement XML serialization and deserialization. The data contract serialization and deserialization is handled by Windows Communication Foundation (WCF).

In order to serialize complex data types, you must define them as data contracts.

## X++ Types

X++ provides support for data contract serialization through the following attributes.

  - DataContractAttribute – This attribute is applied to an X++ class and specifies that the class can be used as a data contract (that it should be serialized).

  - DataMemberAttribute – This attribute is applied to a parm method on an X++ data contract class and specifies that the data member should be serialized. The attribute can be applied to public and instance methods, as long as the method uses a get/set pattern that contains one optional parameter. The data type of the return type and the parameter should be the same. For example, \[DataMemberAttribute\] Int parmXX(int \_x = x)

The X++ data contract attributes function just as the data contract attributes for .NET types. For more information, see [Using Data Contracts](http://go.microsoft.com/fwlink/?linkid=139795).

The following X++ constructs can be used implicitly as data contracts and do not require markup with the data contract attributes:

  - Primitive types such as str, int, int64, real, guid, utcdatetime, and date. Primitive types are shared between services on the same integration port and stored in a shared types .xsd file.

  - Extended data types.

  - Enumerations including X++ boolean.

  - Collections in which all elements are the same type and all elements are of a type that is a valid data contract. This includes the Array class, which is part of Collections.

  - Tables and views. All columns and array fields are exposed as a System.Data.Dataset.

## .NET Types

Any .NET type that can be serialized by WCF can be used as a parameter or return type by a service in Microsoft Dynamics AX. By default, WCF uses the Data Contract Serializer to serialize and deserialize data. For more information about what types are supported by WCF, see [Types Supported by the Data Contract Serializer](http://go.microsoft.com/fwlink/?linkid=128325).

To use .NET types as parameters or return types in X++, you must first create a .NET assembly that contains the .NET data contract classes that have been decorated with the data contract attributes. You then add this assembly as a reference in the AOT, and you can use the data contracts in X++ service operations.


> [!NOTE]
> <P>When using the <STRONG>DataContractSerializer</STRONG>, WCF serializes <STRONG>DateTime</STRONG> values as Coordinated Universal Time (UTC). When you use <STRONG>DateTime</STRONG> values in a data contract, you must pass them as UTC values and convert to local time in the client that calls the service.</P>



## See also

[Walkthrough: Exposing an X++ Class as a Data Contract](walkthrough-exposing-an-x-class-as-a-data-contract.md)

