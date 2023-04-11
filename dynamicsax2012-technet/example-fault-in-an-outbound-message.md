---
title: 'Example: Fault in an Outbound Message'
TOCTitle: 'Example: Fault in an Outbound Message'
ms:assetid: 88e4978e-93a3-4cf2-9044-e302d495e085
ms:mtpsurl: https://technet.microsoft.com/library/Cc602982(v=AX.60)
ms:contentKeyID: 35246280
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example: Fault in an Outbound Message 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When the Application Integration Framework (AIF) receives and processes an inbound message, it generates an outbound message in response. If any error has occurred in processing the message, the service can generate information about the error to include in the response. This topic describes the \<Fault\> tag that occurs in outbound messages that report an error in the corresponding inbound message.

## Outbound \<Fault\> Example

The following XML code example shows a \<Body\> tag section that contains a \<Fault\> tag. The \<Text\> tag contains the textual information that you can use to diagnose the problem.

``` xml
<Body>
 <MessageParts xmlns = "https://schemas.microsoft.com/
    dynamics/2008/01/documents/Message">
  <Fault xmlns = "https://schemas.microsoft.com/dynamics/
     2008/01/documents/Fault">
   <Code>RequestFailed</Code>
   <Reason>
    <Text xml:lang = "EN-US"
       >Request Failed. See the Exception Log for details.</Text>
   </Reason>
  </Fault>
 </MessageParts>
</Body>
```

## View the Exception Log

The \<Text\> tag in the previous example instructed the user to view the **Exceptions** log. The log can be viewed in the **Exceptions** form. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Exceptions**. In the **Exceptions** form, you can view information about the module and subsystem where the error occurred, and a description of the error. You can also view information about when the error was logged, the user who is associated with the error, and the form or business logic where the error occurred.

You can include the information in the exception log in the response on an inbound port by setting **Include exceptions in fault** in the **Troubleshooting** area on the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**. For more information, see [Configure troubleshooting options for integration ports](configure-troubleshooting-options-for-integration-ports.md).

## XSD Validations

The \<Fault\> tag section is validated against the Fault XSD. You can retrieve XSDs for common schemas from your Microsoft Dynamics AX installation. The path of the directory resembles the following:

\\Program files\\Microsoft Dynamics AX\\60\\Server\\\<MicrosoftDynamicsAX installation ID\>\\bin\\Application\\Share\\Include

## See also

[Message Body](message-body.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

