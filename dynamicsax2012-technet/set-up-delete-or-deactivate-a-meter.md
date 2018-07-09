---
title: Set up, delete, or deactivate a meter
TOCTitle: Set up, delete, or deactivate a meter
ms:assetid: 2d62a8e8-651b-4bfa-af19-48a0bc7b255b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208516(v=AX.60)
ms:contentKeyID: 36056260
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up, delete, or deactivate a meter [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Set up a meter

Many machines, extraction devices, and emission points have meters that record the movements of a substance over time. Use the **Meters** form to create new meters and to change the activation status of current meters.

When you create a meter, a new meter reading is created automatically. The date of the new reading is set to the date that the meter was created and the quantity is set to zero. If a process involves multiple incoming substances, the process can have multiple meters. You can convert this information into a substance flow.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Meters**.

2.  Click **New** to create a new meter.

3.  If necessary, enter a numeric ID for the meter.
    

    > [!NOTE]
    > <P>The numeric ID for the meter is generated automatically unless you selected the <STRONG>Manual</STRONG> check box when you created the number sequence code.</P>



4.  Select the substance for which you are creating the meter and enter a description. Select information in the fields to describe the meter’s function, substance type, and substance flow direction.

5.  Select the source and destination processes for the substance.

6.  Select the **Active** check box to activate the meter, and then select the meter type.
    
    Select **Verification** if you are using the meter for auditing purposes and not directly for reporting.

7.  Enter the frequency, and then select the interval to use for meter entry.
    
    For example, if you enter the number 4 for the frequency and select week for the interval, every four weeks a meter entry for this substance will be recorded.

## Delete a meter

You can delete a meter only if no readings have been recorded for it, or if you have deleted previously recorded readings.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Meters**.

2.  Select the meter that you want to delete, and then click **Delete**.

## Deactivate a meter

You can lose data when a meter is reset, if it exceeds its maximum value, or if you replace it. To avoid losing the data, you can deactivate a meter and replace it with a new one. You can activate or deactivate a meter at any time.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Meters**.

2.  On the **Details** tab, clear the **Active** check box.

## See also

[Meters (form)](https://technet.microsoft.com/en-us/library/hh227567\(v=ax.60\))

[Set up environmental processes](set-up-environmental-processes.md)

[Set up substances for environmental tracking](set-up-substances-for-environmental-tracking.md)

[Set up substance categories](set-up-substance-categories.md)

[Set up substance flows between processes](set-up-substance-flows-between-processes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

