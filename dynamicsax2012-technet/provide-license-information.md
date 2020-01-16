---
title: Provide license information
TOCTitle: Provide license information
ms:assetid: 16e3bec8-88c8-4602-84dd-c2b0a9915a76
ms:mtpsurl: https://technet.microsoft.com/library/Aa496447(v=AX.60)
ms:contentKeyID: 35132557
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Provide license information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

License codes and configuration keys are used to control the features and functionality that are available in Microsoft Dynamics AX. Large sets of functionality, such as modules, are controlled by license codes. Many license codes, in turn, enable configuration keys that allow you to enable and disable functionality at a more detailed level. Use the procedures in this topic to enter or modify information about license codes.


> [!NOTE]
> <P>License codes and configuration keys are not part of the licensing model for Microsoft Dynamics AX 2012. They are used only to enable and disable functionality. For more information about licensing in Microsoft Dynamics AX 2012, see the <A href="http://go.microsoft.com/fwlink/?linkid=228374">Pricing and licensing guide</A> and the <A href="http://go.microsoft.com/fwlink/?linkid=228377">Software license terms</A>.</P>



## Import license information

Import license information from a license file provided by Microsoft.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 and AX 2012 R2, importing a new license file does not change existing settings. For example, if a license code was disabled before you imported the new license file, it will remain disabled after you import.</P>



1.  Click **System administration** \> **Setup** \> **Licensing** \> **License information**. –or– Open the **License information** form from the initialization checklist or the upgrade checklist.

2.  Click **Load license file** to import the license codes from a file.
    
    The **Load license file** dialog box appears.

3.  Click the folder icon and browse for the license file.
    

    > [!NOTE]
    > <P>We recommend that you store the license file in a secure location that is known only to Microsoft Dynamics AX administrators.</P>



4.  Click **OK**. A message appears and asks whether you want to synchronize the database.

5.  Click **Yes**.

6.  Close the **License information** window.

## Enter license information

As an alternative to importing the license information, you can enter the license information manually.

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License information**. –or- Open the **License information** form from the initialization checklist or the upgrade checklist.

2.  Enter the name of the license holder, the system's serial number, and the expiration date. The information is in the license document.

3.  On the **System** tab, enter the license code and verify that the **Status** field displays the expected text.
    

    > [!IMPORTANT]
    > <P>The first four entries (name of the license holder, the system's serial number, expiration date, and license code) determine what appears in the remaining codes. Therefore, they must be entered correctly.</P>



4.  Enter the remaining codes.
    
    For each, review the **Status** field to make sure that the code is accepted.

## Modify license information

If you modify the information in the **License information** form, we recommend that you restart the AOS.

If your license includes specific languages, you must restart the AOS after importing the license file or entering license information. Restarting the AOS ensures that the correct languages are listed in the **Options** form (**Microsoft Dynamics AX** \> **Tools** \> **Options...**). If you do not restart the AOS, end users can select unavailable languages, which would prevent the Microsoft Dynamics AX client from starting.

If you enter license information that is not valid for your default language, you will not be able to start the Microsoft Dynamics AX client. If this occurs, a system administrator must change your default language. Alternatively, you can start the client through the command line and use the -language parameter. (For example, ax32.exe -language=ES.) For more information about how to use this parameter, see [Client configuration commands](client-configuration-commands.md).

  


