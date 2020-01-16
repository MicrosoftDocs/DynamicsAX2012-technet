---
title: Install Retail Modern POS
TOCTitle: Install Retail Modern POS
ms:assetid: d1f8a90d-30c8-4f58-81b5-9ff958f68fe5
ms:mtpsurl: https://technet.microsoft.com/library/Dn741434(v=AX.60)
ms:contentKeyID: 62219711
author: Khairunj
ms.date: 07/24/2015
mtps_version: v=AX.60
---

# Install Retail Modern POS 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail Modern POS is a point of sale application designed for Windows 8.1 computers, laptops, and more. It is touchscreen ready and low on overhead, while providing the full functionality of an integrated interface with Retail. This section includes the information about how to install Retail Modern POS.


> [!IMPORTANT]
> <P>The RTM release of Modern POS was delivered in Microsoft Dynamics AX 2012 R3 Cumulative Update 8. If you installed a pre-release copy of Modern POS, you must uninstall the pre-release application prior to installing the RTM application that is included in AX 2012 R3 CU8.</P>



## Before you install Retail Modern POS

  - If you installed a pre-release copy of Modern POS, you must completely uninstall the pre-release application prior to installing the RTM application that is included in AX 2012 R3 CU8.

  - Retail Modern POS clients must be able to connect to a computer that is running Microsoft Dynamics AX Retail Server or to a channel database. Requirements for connecting through a Retail Server include:
    
      - Verify that Retail Server is installed on a computer at the head office.
    
      - Locate the URL for your Retail Server installation. You must specify this URL Setup for device activation. By default, the URL is in the format: https://\<server name\>:port/\<name of web application\>/v1 as it will be required for device activation.
    
      - 
        

        > [!IMPORTANT]
        > <P>Install <A href="https://support.microsoft.com/kb/2703853">Microsoft Sync Framework hotfix 2703853</A> on all computers on which you install the Retail Modern POS. This hotfix can prevent potential data loss when synchronizing Retail offline databases with the channel database.</P>



  - In AX 2012 R3 CU8, set up a register and a device to represent the Modern POS computer or device. For more information, see Setting up Retail Modern POS. Be sure to select a Modern POS Windows 8 layout for the register and a Windows 8 client or Windows 8 phone device type.

  - You do not have to install Retail Modern POS in a domain. You can install it as part of a work group on a single computer.

  - Verify that WinJS and VCLibs libraries are installed on the device where you want to install this component. For more information, see [Manually install Retail Modern POS prerequisites](manually-install-retail-modern-pos-prerequisites.md).

## Install Retail Modern POS


> [!NOTE]
> <P>When installing Retail Modern POS on a domain-joined computer, you must ensure that&nbsp;the computer can connect to the domain controller during the installation process.</P>



Use this procedure to install the default Microsoft Dynamics AX Retail Modern POS app on a supported device. If you install other Microsoft Dynamics AX components at the same time, the installation pages vary, depending on the components that you are installing. For information about how to install a customized Retail Modern POS app on a supported device, see the next section in this topic.


> [!NOTE]
> <P>If you installed a pre-release copy of Modern POS, you must completely uninstall the pre-release application prior to installing the RTM application that is included in AX 2012 R3 CU8.</P>



1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on this computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Provide a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  On the **Select components** page, select **Retail Retail Modern POS**, and then click **Next**.

5.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

6.  After the installation is completed, click **Finish** to close the wizard.


> [!NOTE]
> <P>If you install Retail Modern POS on a Windows 8.1 Professional or non-domain joined computer, Setup might prompt you to provide an enterprise side-loading key. This key is included with your Enterprise Volume License.</P>



## Install a customized Retail Modern POS app on a computer

The Retail SDK includes source samples and tools to help you customize the Retail Modern POS app for Windows 8.1. If you customize a Retail Modern POS app then you must use on the following methods to side-load it to supported devices.

  - [Windows Intune](http://go.microsoft.com/fwlink/?linkid=397194)

  - System Center Configuration Manager

  - A third-party mobile device management service

  - Create a custom installer to deploy the app

  - Install the app by using Windows PowerShell scripts

For more information about customizing and installing a customized Retail Modern POS app, see [Retail Modern Point of Sale](retail-modern-point-of-sale.md) in the Retail Modern POS documentation roadmap.

## After you install Retail Modern POS

Start the Microsoft Dynamics AX Retail Modern POS app. In the **Device Activation** page, enter information about the register and device for the Windows 8.1 computer or device, and credentials for a manager of the store that the register is associated with. If you are connecting through Retail Server, enter its URL. For information about connecting through a database, see [Configure Retail Modern POS for direct database connectivity](configure-retail-modern-pos-for-direct-database-connectivity.md).

If you encounter connectivity issues after installing, see the topic [Troubleshoot connectivity problems for Retail Modern POS devices](troubleshoot-connectivity-problems-for-retail-modern-pos-devices.md).

## Uninstall Retail Modern POS

You can uninstall Retail Modern POS either by running AxSetup.exe and selecting the component for removal, or by uninstalling it from Add or Remove Programs.


> [!NOTE]
> <P>If multiple Windows users have been using an installation of Retail Modern POS, we recommend that you start with a reimaged computer whenever possible. Alternatively, you must explicitly remove the application for every user that logged in to the computer. Do this by right-clicking the application on the Start screen. When that is complete, you can remove the installer from Add or Remove Programs.</P>



## See also

[Configure Retail Modern POS for direct database connectivity](configure-retail-modern-pos-for-direct-database-connectivity.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  


