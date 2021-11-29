---
title: Check prerequisites
TOCTitle: Check prerequisites
ms:assetid: a1ae0f82-c843-491b-8367-19de11f59fc5
ms:mtpsurl: https://technet.microsoft.com/library/Gg731884(v=AX.60)
ms:contentKeyID: 35132793
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Check prerequisites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Run the prerequisite validation utility for Microsoft Dynamics AX to determine whether a computer meets the requirements to install a Microsoft Dynamics AX component. You can run the utility before you install any components in your environment. If requirements are not met, the utility helps you install or configure most prerequisites. Additionally, you can view or print a report that shows the results of the prerequisite validation.

Prerequisite validation is also built into Setup. Therefore, the same prerequisites are validated when you install a component by using the Setup wizard.


> [!NOTE]
> <P>The prerequisite validation utility validates the software prerequisites that Microsoft Dynamics AX depends on. However, the utility does not verify whether Microsoft Dynamics AX components that are also required are installed or configured. For example, the utility verifies whether a supported version of Windows is installed, but does not verify whether an Application Object Server (AOS) is running in the environment. Prerequisite Microsoft Dynamics AX components are validated when you run Setup.</P>



To review the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

Use the following procedure to run the prerequisite validation utility.

1.  Start Microsoft Dynamics AX Setup.

2.  Under **Prepare**, click **Validate system requirements**.
    

    > [!NOTE]
    > <P>To avoid errors, run only one instance of the utility at a time.</P>



3.  The **Prerequisite validation** page is displayed. Select the components that you plan to install on the local computer, and then click **Next**.

4.  The **Prerequisite validation results** page is displayed. Each prerequisite is assigned one of the following statuses.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Status</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Success</strong></p>
    <img src="images/Gg731884.PrereqSuccessIcon(AX.60).png" title="Prerequisite checker success icon" alt="Prerequisite checker success icon" /></td>
    <td><p>The local computer meets the prerequisite.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Error</strong></p>
    <img src="images/Gg731884.PreReqErrorIcon(AX.60).png" title="Prerequisite checker failure icon" alt="Prerequisite checker failure icon" /></td>
    <td><p>The local computer does not meet the prerequisite. You cannot install the component until this prerequisite is installed or configured.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warning</strong></p>
    <img src="images/Gg731884.PreReqWarningIcon(AX.60).png" title="Prerequisite checker warning icon" alt="Prerequisite checker warning icon" /></td>
    <td><p>The local computer does not meet the prerequisite, but you can still install the Microsoft Dynamics AX component.</p></td>
    </tr>
    </tbody>
    </table>
    
    For more information about a prerequisite, click its status. For information about all the prerequisites that were validated, click **View report** to display the Microsoft Dynamics AX **Prerequisite check report**. Both options provide a description of the prerequisite, the validation status, and recommendations for resolving any problems.

5.  Resolve prerequisite issues. For many errors and warnings, the prerequisite validation utility can attempt to resolve the issue for you.
    
      - If a link is available in the **Download** column, click it to download and install the missing prerequisite. Internet access is required to download some prerequisites that are not included on the installation media. In some cases, the download starts immediately when you click the link. In other cases, a download page is displayed when you click the link.
        

        > [!NOTE]
        > <P>If network or computer security prevents a prerequisite from being downloaded from the utility, you must download the prerequisite by using another method. Click the <STRONG>Error</STRONG> link on the prerequisite validation page to obtain the download URL.</P>

    
      - If a check box is available in the **Configure** column, select it, and then click the **Configure** button to resolve the issue.
    
    Some prerequisites depend on other prerequisites. In these cases, the prerequisites must be installed or configured in a specific order. For example, the Windows Search Service must be installed before it can be started.

6.  After you have resolved prerequisite issues, click **Revalidate** to run the prerequisite validation again.

7.  When you have finished validating prerequisites, click **Close**.


> [!IMPORTANT]
> <P>Prerequisite software that is installed or configured by the prerequisite validation utility may not include the latest updates. We strongly recommend that you run Windows Update to identify and install the latest updates before you continue with the installation of Microsoft Dynamics AX.</P>



## See also

[Troubleshoot prerequisite issues](troubleshoot-prerequisite-issues.md)

  


