---
title: Clean up old time and attendance registrations
TOCTitle: Clean up old time and attendance registrations
ms:assetid: 97d174b1-d6c4-4d94-9091-be9628679b2d
ms:mtpsurl: https://technet.microsoft.com/library/Aa498435(v=AX.60)
ms:contentKeyID: 39519239
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Clean up old time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Registrations can accumulate in Microsoft Dynamics AX over time, and can reduce the performance of the application. Therefore, we recommend that you clean up old registrations periodically.

You can remove old registrations in the following ways:

  - You can delete them.

  - You can export them to a file.

  - You can transfer them to an archive table.


> [!IMPORTANT]
> <P>The clean-up function does not delete data that is not processed. Make sure that you do not delete registrations that may be required later for documentation purposes.</P>



## Clean up registrations

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Update** \> **Clean up registrations**.
    
    –or–
    
    Click **Production control** \> **Periodic** \> **Clean up** \> **Clean up registrations**.
    
    –or–
    
    Click **Production control** \> **Inquiries** \> **Registrations** \> **Raw registrations archive**. On the toolbar, click **Clean up registrations**.

2.  In the **Cleanup mode** field, select how you want to handle the old registrations:
    
      - Select **To table** to move the registrations to another table in Microsoft Dynamics AX. The registrations are transferred to the **Raw registrations archive** form.
    
      - Select **To file** to move the registrations to an external file.
    
      - Select **Delete** to permanently delete the registrations.

3.  In the **Maximum age** field, enter the maximum age, in days, of registrations that are kept in the raw registrations table. For example, if you enter the number 20, all registrations that are more than 20 days old are archived according to your selection in the **Cleanup mode** field.

4.  If you select **To file** in the **Cleanup mode** field, enter a file name, or select an existing file, in the **File name** field.

## View archived registrations for a worker

If you have transferred registrations to an archive table, you are still able to view them.

1.  Click **Production control** \> **Inquiries** \> **Registrations** \> **Raw registrations**.

2.  Select the worker, and then click **Archive**.

3.  Select the date for which you want to view archived registrations.


> [!TIP]
> <P>The following path shows another way to open the <STRONG>Raw registrations archive</STRONG> form. Click <STRONG>Production control</STRONG> &gt; <STRONG>Inquiries</STRONG> &gt; <STRONG>Registrations</STRONG> &gt; <STRONG>Raw registrations archive</STRONG>.</P>



## See also

[About time and attendance registrations](about-time-and-attendance-registrations.md)

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

  


