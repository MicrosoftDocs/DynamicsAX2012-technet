---
title: About the AIF Pipeline and Transforms
TOCTitle: About the AIF Pipeline and Transforms
ms:assetid: 6be5dc9c-154d-487f-8037-0a2b1c55ff6e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg840969(v=AX.60)
ms:contentKeyID: 35244796
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# About the AIF Pipeline and Transforms 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3. For more information, see the section later in this topic.</P>



Application Integration Framework (AIF) provides the flexibility to transform a message as it comes into or goes out of Microsoft Dynamics AX. For an introduction to AIF messages and transforms, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).


> [!NOTE]
> <P>This topic discusses the AIF pipeline and transforms in terms of inbound requests. For outbound requests, the same transformation components can be implemented but they are called in the reverse order.</P>



You can create different types of transform components and then specify the order in which they will be called to transform data. The transform components fall into the following two categories:

  - **Transforms (transform components that are called before the message is stored in the gateway queue)** The gateway queue manages the processing of messages. This is where messages are stored before they are processed by the service operation. The gateway queue can only accept XML messages. For example, an inbound message in another format such as a comma-separated values (CSV) file must be transformed into XML in the AIF pipeline before it reaches the gateway queue. In addition, if a message contains multiple requests, each [request must be correctly formatted](aif-messages.md) as an individual message before it reaches the gateway queue. Transform components that are called before the message reaches the gateway queue include the following:
    
      - .NET assembly
    
      - XSLT
    
    These components are typically used to change the format of the message. For example, if the inbound message is a CSV file that contains data about multiple customers, your pipeline could contain two components. The first is a .NET assembly that converts the data into an XML file. The second is an XSLT that applies the appropriate header information to the customer data in that XML file so that the multiple requests can be processed by the gateway queue.

  - **Pipelines (transform components that are called after the message is retrieved from the gateway queue)** The three types of transformations you can implement after the message is processed in the gateway queue include the following:
    
      - XSL transforms
    
      - .NET assembly transforms
    
      - Value substitution
    
    Typically, these components are used to transform the content of a message. For example, if you have an inbound message that contains customer records, your AIF pipeline could contain an XSLT that updates an element in the XML based on the value of the customer status element. As the message continues through the pipeline, you may have a value substitution that converts your trading partner’s currency code into the currency code used by Microsoft Dynamics AX. Finally, your AIF pipeline could contain a custom component that writes information to a log for each customer record that is processed. This custom component must be an X++ class that implements the [AifPipelineComponent](https://technet.microsoft.com/en-us/library/gg851722\(v=ax.60\)) interface.


> [!NOTE]
> <P>The AIF pipeline is completely flexible, and all the components are optional. Your AIF pipeline can contain none, one, or more than one of any of the available components.</P>



## Message Transformation before the Gateway Queue

Before an inbound message reaches the gateway queue, there are two types of transformation components that you can implement: a .NET assembly or an XSLT. For information about how to configure transforms in an exchange, see [Configure processing options](configure-processing-options.md).

## .NET Assembly

You can use a .NET assembly to transform data to and from any format. This enables you to process non-XML data such as text files, CSV files, tab-delimited files, and so on in AIF. Before adding a binary transform to the pipeline, you must create an assembly that contains a class that implements the ITransform interface. This class contains the code that you write to transform and customize the data. You pass data into this class in a stream, transform it, and then pass the transformed data out of the class in a stream. Then the stream can be processed by the next pipeline component (if there is one).

After you have created the .NET assembly, you must import it for use in the AIF pipeline. For more information, see [Walkthrough: Creating a .NET Assembly Transform](walkthrough-creating-a-net-assembly-transform.md).

## XSLT

XSL transforms use an XSLT to transform an XML message. Before adding an XSL transform to the pipeline, you must create an XSLT file and import it into Microsoft Dynamics AX. After you have created the XSLT, you must import it for use in the AIF pipeline. You can import an XSLT by using one of the administration forms (either the **Inbound ports** form or the **Outbound ports** form), or from the development workspace. For more information about how to import an XSLT in the development workspace, see [How to: Import an XSLT Transform](how-to-import-an-xslt-transform.md). For more information about how to import an XSLT using one of the administration forms, see the section “Manage transforms” in [Configure processing options](configure-processing-options.md).

## Message Transformation after the Gateway Queue

After an inbound message leaves the gateway queue, there are three types of transformation components that you can implement: XSLT, value substitution or custom component. You add XSLTs, value lookups, and custom components to the pipeline by using the **Inbound pipelines** or the **Outbound pipelines** forms. For more information, see “Configure pipelines” in [Configure processing options](configure-processing-options.md).

## XSL

XSL transforms enable you to transform message data after it has left the message queue. For more information, see “Configure transforms” and “Manage pipeline XSLT transforms” in [Configure processing options](configure-processing-options.md).

## Value Substitution

Value lookups enable you to replace a value in a message with another value. For example, you may have an inbound message that specifies Europe for the CustCurrencyCode but your system uses the code EUR. You can create a value substitution that changes the value Europe to EUR before saving the data to the database.

This is especially useful in business-to-business (B2B) scenarios where the value of a code such as CustCurrencyCode in your Microsoft Dynamics AX installation differs from the value that is used by your trading partner. Value lookups are defined for a single extended data type (EDT). Any values found in a message that match the value specified in the value look and are of the same extended data type will be transformed. Value lookups are defined in the **Value substitution maps** form. Click **System administration** \> **Setup** \> **Value substitution maps** For more information, see [Configure value substitution maps](configure-value-substitution-maps.md).

## Custom Component

A custom component transformation enables you to call a custom X++ class from the AIF pipeline to perform processing. This processing could entail transforming the message data in some way or it could entail performing tasks related to the message. For example, you could write a custom component to save processing details about messages to a table in Microsoft Dynamics AX.

AIF pipeline custom components are created by using X++ and must implement the AifPipelineComponent interface.

## XSLT processing in AX 2012 R3

In earlier versions of Microsoft Dynamics AX 2012: the XML declaration was omitted from the output document by default when AIF applied XSL transforms. In AX 2012 R3 you control whether the XML declaration is output or not by using the omit-xml-declaration attribute of the \<xsl:output\> element in the XSLT file. The default is to output the XML declaration. In other words, the \<XML\> tag is included in output documents by default.

For example, in AX 2012 R3 if you do not specify a value for the omit-xml-declaration attribute, the default value No is used and the XML declaration is included in the output document.

For more information about the XSLT elements, including the [xsl:output element](http://go.microsoft.com/fwlink/?linkid=393920%26clcid=0x409), see [XSLT Elements](http://go.microsoft.com/fwlink/?linkid=393918%26clcid=0x409).

## See also

[How to: Import an XSLT Transform](how-to-import-an-xslt-transform.md)

[Importing Updated .NET Assembly Transforms](importing-updated-net-assembly-transforms.md)

  


