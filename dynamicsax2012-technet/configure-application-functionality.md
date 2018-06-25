---
title: Configure application functionality
TOCTitle: Configure application functionality
ms:assetid: 2cc47a88-0e25-48ba-8aa9-3576de1b5cb5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496468(v=AX.60)
ms:contentKeyID: 35132590
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure application functionality [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The administrator can enable or disable configuration keys to control the features and functionality that are available in Microsoft Dynamics AX.

Each configuration key controls access to a specific feature. When a configuration key is disabled, the feature is removed from the user interface. We recommend removing unused functionality.

For information about a specific configuration key, see the [License code and configuration key reference](license-code-and-configuration-key-reference.md).


> [!NOTE]
> <P>Features that are specific to a country or region are enabled and disabled based on the primary address of the legal entity. For more information, see <A href="create-or-modify-a-legal-entity.md">Create or modify a legal entity</A>.</P>



## Set up configuration keys

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**. –or– Open the **Configuration** form from the initialization checklist.
    
    The form displays a list of the configuration keys that you can use to enable features. Some configuration keys have a parent key. If the parent key is disabled, the child keys are also disabled.

2.  To enable a configuration key, select the check box next to the relevant feature.
    
    Configuration keys that are controlled by license codes are indicated by a red padlock symbol. These keys control basic functionality and cannot be disabled. However, child keys of license code-controlled keys can be disabled.
    
    Click **Standard** to discard your changes and revert configuration keys to their original state.

3.  Click **OK** to save changes and close the form.

4.  If you have modified any configuration keys, the **License and configuration differences** form is displayed. Use this form to review the application changes that are caused by the configuration changes.
    
    We strongly recommend that you restart the AOS after you change configuration keys that affect database tables or fields. Click the **Tables and fields** tab in the **License and configuration differences** form to verify whether tables and fields are affected.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

