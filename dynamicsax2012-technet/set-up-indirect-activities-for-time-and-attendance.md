---
title: Set up indirect activities for time and attendance
TOCTitle: Set up indirect activities for time and attendance
ms:assetid: d297e057-2603-4500-a7e4-a6fa809875d4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551048(v=AX.60)
ms:contentKeyID: 36059507
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- category
---

# Set up indirect activities for time and attendance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Indirect activities are grouped in categories. Each category can only contain indirect activities of the same registration type, for example, jobs or breaks.

## Create an indirect activity

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Indirect activity categories**.

2.  Press CTRL+N, or click **New** on the toolbar.
    

    > [!NOTE]
    > <P>If a relevant category already exists, select that category, and see step 5.</P>



3.  Fill out the **Category** and **Description** fields.

4.  In the **Reg. type** list, select the relevant registration type.

5.  Click **Activities**.

6.  Press CTRL+N to create a new activity.

7.  Insert a name or identification of the indirect activity in the **Activity** field.

8.  Insert a description of the activity in the **Description** field.

9.  On the **General** tab, select the **Registration** check box only if workers are to make registrations on the indirect activity.

10. On the **General** tab, if relevant, select accounts that will be used for ledger posting in the **Main account** and **Offset account** fields.

11. On the **General** tab, if you are creating an activity of Registration type **Job**:
    
      - In the **System function** field, select the relevant function for this indirect activity.
        

        > [!NOTE]
        > <P>The standard value in this field is <STRONG>Jobs</STRONG>. If the indirect activity is an ordinary job or task that lasts for a while, such as a meeting or a machine repair job, select <STRONG>Jobs</STRONG> in this field.</P>



12. On the **General** tab, if you are creating an activity of Registration type **Break**:
    
    1.  In the **Cancel break** field, select if the break activity can be used for canceling breaks.
    
    2.  Select the **Paid** check box if the break is a paid break.
    
    3.  In the **Break** field, insert the duration of the break in minutes.
    
    4.  In the **Break tolerance** field, enter the number of minutes past the duration of a break that a worker can make an end break registration before a deduction is made to his or her pay.
        
        Example: Breaks are defined as lasting 15 minutes, and the break tolerance is 3 minutes. If a worker makes an end break registration 18 minutes after he or she started the break, a deduction in pay will not be made. However, if the worker makes an end break registration 25 minutes after the start of the break, seven minutes of an hour’s pay will be deducted.

13. If you are creating an activity of the registration type **Switch code**, you can do the following on the **General** tab:
    
    1.  Select the **Approve switchcode** check box if the use of this switch code requires manual approval by a supervisor or manager.
    
    2.  Click the **Exclude switch codes** button to set up invalid switch code combinations. These are code combinations that cannot be registered on the same day. This helps makes sure that a worker cannot make registrations on two switch codes on the same profile date, which are not meant for use in the same work situation.
        
        Example: One switch code may trigger double overtime pay when the production department asks workers to work extra hours in order to keep up with demand. Another switch code may be used to convert overtime into flexible hours. In this example, the company does not want the workers to convert overtime into flexible hours because all working hours are needed in production. Therefore, these two switch codes will exclude each other.
        
        1.  In the **Switch code** field, select the switch code that will exclude another switch code.
        
        2.  In the **Excludes switch code** field, select the switch code that will be excluded. This means that this switch code cannot be registered by a worker on the same profile date if the switch code selected in the **Switch code** field has already been registered.

14. If necessary, set up dimensions on the **Financial dimensions** tab.

## Cost of indirect activities

For each indirect activity you can define an hourly cost that will be calculated when workers make registrations on the indirect activity.

To define an hourly cost for an indirect activity, click **Cost price** in the **Activities** form after you have created the indirect activity.

## On call

If you want to track how many times a worker is called on during a work shift, you must create some on-call indirect activities. The worker must register on each activity, depending on the first, second, and third on-call activity. You can also set up different pay rates for each on-call activity.

## See also

[About indirect activities for time and attendance](about-indirect-activities-for-time-and-attendance.md)

[Indirect activities (form)](https://technet.microsoft.com/en-us/library/aa597338\(v=ax.60\))

[Indirect activities setup (form)](https://technet.microsoft.com/en-us/library/aa600187\(v=ax.60\))

[Indirect activity cost price (form)](https://technet.microsoft.com/en-us/library/aa596823\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

