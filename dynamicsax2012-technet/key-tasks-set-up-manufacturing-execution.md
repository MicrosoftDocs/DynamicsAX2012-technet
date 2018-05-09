---
title: 'Key tasks: Set up manufacturing execution'
TOCTitle: 'Key tasks: Set up manufacturing execution'
ms:assetid: bdada46b-1d4e-4213-907f-20fcae1c3e85
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242779(v=AX.60)
ms:contentKeyID: 36059158
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production
- manufacturing execution
- shop floor
---

# Key tasks: Set up manufacturing execution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure manufacturing execution parameters and settings in **Production control** to register worker time and item consumption on production jobs. This topic describes how to set up the following manufacturing execution features:

  - General parameters required by production features

  - Production parameters that affect manufacturing execution processes

  - Registration forms for providing feedback

  - Allocation keys for bundling jobs

## What do you want to do?

Learn more about...

Set up the manufacturing execution parameters that are required for production

Set up production parameters – General parameters

Set up production parameters – Start parameters

Set up production parameters – Operations parameters

Set up production parameters – Report as finished parameters

Set up production parameters for validating quantities

Configure a form for registrations

Connect a worker to a specific registration form

Set up allocation keys for bundling jobs

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

[About production parameters in Manufacturing execution](about-production-parameters-in-manufacturing-execution.md)

[About allocation keys](about-allocation-keys.md)

[About production feedback](about-production-feedback.md)

## Set up the manufacturing execution parameters that are required for production

Before you set up production-related parameters, you must set up the manufacturing execution parameters that are required for using production features.

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Manufacturing execution parameters**.

2.  In the **General** area, specify a method of identification for workers by selecting either the **Use password** or **Use badge ID** check box.

3.  In the **Report as finished** field, select the status to display when a worker reports feedback on production jobs. This feedback is reported in the **Job registration** form.

For information about other fields in this form, see [Manufacturing execution parameters (form)](https://technet.microsoft.com/en-us/library/hh209488\(v=ax.60\)).

Back to top

## Set up production parameters – General parameters

Production parameter settings should always reflect your production environment. Production parameters determine when raw materials are deducted from stock in the production process. These parameters also determine what information is reported in other areas in Microsoft Dynamics AX regarding the execution and completion of production orders in manufacturing execution.

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.

2.  In the **Production parameters** form, in the **General** area, in the **Parameter usage** field, select whether to use company parameters or site parameters.

3.  In the **Bundle type** field, select the allocation key to use if workers make registrations on more than one job at a time.
    
    For more information about how to create allocation keys for a specific site, production unit, or resource, see “Set up allocation keys for bundling jobs,” later in this topic.

4.  Select the **Post time automatically** check box if you want the system to post all journals when registrations are approved and transferred.

5.  In the **Time journal** field, select a journal type. The journal type that you select depends on the option that is selected in the **Job level** field in the **Operations** area of this form:
    
      - If **Route** is selected, select the route journal in the **Time journal** field.
    
      - If **Job** is selected, select the job journal in the **Time journal** field.
    
    **Route** and **Job** refer to scheduling methods that are used in production planning. For more information, see [About working with routes in production](about-working-with-routes-in-production.md) and [About job scheduling](about-job-scheduling.md).
    

    > [!IMPORTANT]
    > <P>If you change the setting in the <STRONG>Job level</STRONG> field in the <STRONG>Operations</STRONG> area, you must update the <STRONG>Time journal</STRONG> field to reflect the change. You must also synchronize the job table. For more information, see <A href="synchronize-the-job-table.md">Synchronize the job table</A>.</P>



6.  If the production workers are paid based on piecework, select the relevant pay rate formula in the **Piecework rate formula** field.

7.  If you want to specify piecework orders separately, select the **Specify production order** check box. If you clear this check box, all production orders are handled as piecework orders, and the pay rate that is defined in the **Piecework rate formula** field is used.

8.  Select the **Cost category** check box if you want to use cost categories to calculate costs on production orders or projects. If you clear this check box, real cost is applied.
    

    > [!NOTE]
    > <P>Real cost can be used only if you use the payroll functionality in <STRONG>Time and attendance</STRONG>. In that case, production costs are calculated based on time registrations and the hourly cost setup for the workers.</P>



9.  In the **Dimension** field, select whether you want to use the financial dimensions that are connected to a job or to a worker. In Microsoft Dynamics AX, financial dimensions are used to associate data or registrations with specific work areas or locations, such as departments, production areas, jobs, or workers.
    
    The options **Job -\> worker** and **Worker -\> job** indicate a first and second option. If no dimensions exist for the first option, the dimensions for the second option are used.

Back to top

## Set up production parameters – Start parameters

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.

2.  In the **Production parameters** form, in the **Start** area, in the **Update start on-line** field, select the information to report to the **Production control** module when you start a production job or operation.
    
    The selection in this field determines what information a machine operator must enter in the system. Select from the following options:
    
      - **No** – A machine operator does not start operations and jobs. If you select this option, production orders are initiated at a higher level, such as by a production manager. Also, if this option is selected, no jobs are displayed in the **Job registration** form.
    
      - **Status + quantity** – A machine operator starts operations and jobs by using the **Job registration** form. If this option is selected, the operator must indicate the number of items to be produced when an operation or job is started.
    
      - **Status** – Operation and jobs are started by an operator in the **Job registration** form. If this option is selected, an operator can enter both the quantity and the status, but only the status is reported in the system.
        

        > [!NOTE]
        > <P>You must also set a similar parameter in the <STRONG>Report as finished</STRONG> area of the form, in the <STRONG>Update finished report on-line</STRONG> field. Both selections determine when you update the quantity on production orders. Also, the selections in the <STRONG>Automatic BOM consumption</STRONG> fields are related to reporting and updating production feedback. For more information, see <A href="about-production-parameters-in-manufacturing-execution.md">About production parameters in Manufacturing execution</A>.</P>



3.  Select the **Use Manufacturing Execution parameters** check box if you want to use the production parameter setup in manufacturing execution. If you clear this check box, the parameter settings in the **Production control** module are used.

4.  Select the **Open picking list journals** check box if you want to be able to change the picking list before you post it.

5.  Select the **Start production** check box to update the started quantity on a production order.
    

    > [!NOTE]
    > <P>This field is available only if <STRONG>Status + quantity</STRONG> is selected in the <STRONG>Update start on-line</STRONG> field in this area.</P>



6.  Select the **References** check box if you want to automatically start production orders that are attached to the selected production order. If this check box is selected, all related orders start at the same time.

7.  In the **Route card** field, select the route card journal to use for posting time and quantity registrations.

8.  In the **Automatic route consumption** field, select whether the calculated route consumption should be added to the route card journal. Select from the following options:
    
      - **Never** – Do not add the calculated route consumption to the route card journal.
    
      - **Always** – Always add the calculated route consumption to the route card journal.
    
      - **Route group dependent** – Select this option if the settings on the route group determine whether calculated route consumption should be added to the route card journal.

9.  Select the **Post route card now** check box if you want the route card journal to be posted when you start an operation or a job.

10. Select the **End-mark route** check box if you want to automatically post an end marking of the operations and jobs in the route card journal when you start a production.

11. In the **Picking list** field, select the picking list journal to use for posting item consumption.

12.  In the **Automatic BOM consumption** field, select how raw materials are deducted from stock. This parameter must also be set in the **Operations** and **Report as finished** areas of this form.
    

    > [!IMPORTANT]
    > <P>It is important to select the correct combination of parameters to avoid registering erroneous BOM consumption. For example, by selecting the correct combination, you avoid deducting materials two times from stock or not deducting them at all. For information about how different parameter combinations affect item consumption and inventory management, see <A href="about-production-parameters-in-manufacturing-execution.md">About production parameters in Manufacturing execution</A>.</P>



13. Select the **Post picking list now** check box if you want to post automatically generated picking lists immediately.

14. Select the **End-mark picking list** check box to create a picking list that contains end marking lines for the production order. If this check box is selected, no additional item consumption will be posted on the production order.
    

    > [!NOTE]
    > <P>This parameter must also be set in the <STRONG>Report as finished</STRONG> area of this form. The BOM consumption method that is selected in each area determines whether the system end-marks a picking list when you start a production order or when you report it as finished.</P>



15. Select the **Physical reduction** check box to allow for reduction of items from stock down to what is actually available.
    

    > [!NOTE]
    > <P>This field and the <STRONG>Pick negative</STRONG> field are mutually exclusive. If you select one check box, you must clear the other.</P>



16. Select the **Pick negative** check box if you want to allow for negative item consumption. If this check box is selected, items that are not yet registered in Microsoft Dynamics AX can be picked from stock.
    

    > [!NOTE]
    > <P>To use this option, the <STRONG>Physical negative inventory</STRONG> check box must be selected for the item model group. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa577092(v=ax.60)">Item model groups (form)</A>.</P>



17. Select the **Complete picking list journal** check box if you want to update the status of all BOM items to **Finished picking**. This includes items that consumption has not been calculated for.

18. In the **Create journal per** field, select how picking lists are created. Select from the following options:
    
      - **\[Blank\]** – Create one journal for the production order.
    
      - **Route type** – Create a journal for each route in the production order.
    
      - **Oper. No.** – Create a journal for each operation in the production order.

Back to top

## Set up production parameters – Operations parameters

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.

2.  In the **Production parameters** form, in the **Operations** area, in the **Job level** field, select the level of detail for planning and scheduling production orders. Select from the following options:
    
      - **Job** – Use job scheduling of production orders.
    
      - **Route** – Use operations scheduling of production orders. This means that planning is performed on dates only.
        

        > [!NOTE]
        > <P>If you select <STRONG>Job</STRONG> in this field, ensure that <STRONG>Job scheduling</STRONG> is selected in the <STRONG>Scheduling method</STRONG> field in the <STRONG>Automatic update</STRONG> area of the <STRONG>Production control parameters</STRONG> form. If these settings are not the same, no jobs for registration appear in the <STRONG>Job registration</STRONG> form.</P>



3.  In the **Route consumption journal** field, select a journal type. The journal type that you select depends on the option that is selected in the **Job level** field:
    
      - If the **Job level** field is set to **Route**, select the route journal.
    
      - If the **Job level** field is set to **Job**, select the job journal. This journal posts finished items on operations and updates statuses on jobs.
    

    > [!IMPORTANT]
    > <P>If you change the setting in the <STRONG>Job level</STRONG> field, you must update this field to reflect the change. You must also update the <STRONG>Time journal</STRONG> field in the <STRONG>General</STRONG> area of the form.</P>



4.  Select the **Post automatically** check box if you want to post the automatically generated route or job cards immediately.

5.  In the **Register on ...** section, select the check boxes for the job types that must be available for registration in the **Job registration** form. Some of the check boxes in this section are available only if you are using job scheduling.

6.  In the **Automatic BOM consumption** field, select how raw materials are deducted from stock. This parameter must also be set in the **Start** and **Report as finished** areas of this form.
    

    > [!NOTE]
    > <P>It is important to select the correct combination of parameters to avoid registering erroneous BOM consumption. For example, by selecting the correct combination, you avoid deducting materials two times from stock or not deducting them at all. For information about how different parameter combinations affect item consumption and inventory management, see <A href="about-production-parameters-in-manufacturing-execution.md">About production parameters in Manufacturing execution</A>.</P>



7.  In the **Picking list** field, select the picking list journal to use when you post information about BOM consumption.

8.  Select the **Post automatically** check box if you want to post the automatically generated picking list journals immediately.

9.  Select the **Edit journal** check box to enable workers to change a picking list journal before it is posted.

10. Select the **Assistants use secondary operations** check box if you want the system to search for worker IDs among secondary operations when workers are registered as assistants to a resource. Selecting this check box makes sure that an assistant’s registrations are calculated by using the correct cost price if, for example, a resource has a higher hourly cost than the assistant.
    

    > [!NOTE]
    > <P>This field is available only if the <STRONG>Cost category</STRONG> check box is selected in the <STRONG>General</STRONG> area of the form.</P>



Back to top

## Set up production parameters – Report as finished parameters

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.

2.  In the **Production parameters** form, in the **Report as finished** area, in the **Update finished report on-line** field, select the information that you want to report to the **Production control** module when a production job or operation is completed. The selection in this field determines what information a machine operator must report in the system about production feedback. An operator reports the information by using the **Job registration** form.
    
      - **No** – Operations and jobs are not reported as finished by an operator. This means that finished production orders are reported at a higher level, such as by a production manager.
    
      - **Status + quantity** – An operator reports operations and jobs as finished. If this option is selected, the operator must indicate the number of items that were produced when an operation or job is completed. The operator must also update the status of the job.
    
      - **Status** – An operator should update the status of a job or operation when he or she sets it to complete. If this option is selected, the operator can enter both the quantity produced and the status, but only the status is reported in the system.
    
      - **Quantity** – An operator should provide feedback only about the quantity produced. If this option is selected, the operator can enter both the quantity and the status, but only the quantity is reported in the system.
    

    > [!IMPORTANT]
    > <P>The option that you select in this field is related to the option that is selected in the <STRONG>Update start on-line</STRONG> field in the <STRONG>Start</STRONG> area of the form. Additionally, the selections in the <STRONG>Automatic BOM consumption</STRONG> fields are related to reporting and updating production feedback. For information about how different settings affect item consumption and reporting feedback on production orders, see <A href="about-production-parameters-in-manufacturing-execution.md">About production parameters in Manufacturing execution</A>.</P>



3.  Select the **Use Manufacturing Execution parameters** check box if you want to use the production parameters that are set up in the **Manufacturing execution parameters** form. If you clear this check box, the parameter settings in the **Production control** module are used.

4.  In the **Route card** field, select the route card journal to use for posting time and quantity registrations when reporting feedback and completing an operation or job.

5.  In the **Automatic route consumption** field, specify whether the calculated route consumption is added to the route card journal when the operation or job is reported as finished:
    
      - **Never** – Do not add the calculated route consumption to the route card journal. If necessary, route consumption can be manually recorded in a route card journal or a job card journal.
    
      - **Always** – Always add the calculated route consumption to the route card journal.
    
      - **Route group dependent** – Select this option if the settings on the route group determine whether calculated route group consumption should be added to the route card journal. For more information, see [Route groups (form)](https://technet.microsoft.com/en-us/library/aa596433\(v=ax.60\)). If automatic consumption of setup time and process time, and automatic reporting of the finished quantity are selected for the attached route group, a route consumption journal is generated.

6.  Select the **End-mark route** check box if you want to automatically post an end marking of operations and jobs in the route card journal when you report a production order as finished.

7.  In the **Picking list** field, select the picking list journal to use for posting item consumption.

8.  In the **Automatic BOM consumption** field, select how raw materials are deducted from stock. This parameter must also be set in the **Start** and **Operations** areas of this form.
    

    > [!NOTE]
    > <P>It is important to select the correct combination of parameters to avoid registering erroneous BOM consumption. For example, by selecting the correct combination, you avoid deducting materials two times from stock or not deducting them at all. For information about how different parameter combinations affect item consumption and inventory management, see <A href="about-production-parameters-in-manufacturing-execution.md">About production parameters in Manufacturing execution</A>.</P>



9.  Select the **End-mark picking list** check box to create a picking list that contains end marking lines for the production order. If this check box is selected, no additional item consumption will be posted on the production order.

10. In the **Report as finished** field, select the journal to use for posting report as finished information.

11. Select the **End job** check box if you want the production order status to automatically change to **Report as finished** when the last operation or job for the production order is completed. This deletes excess inventory transactions that have a status of **On order** or **Ordered**. The status of the production order changes to **Reported as finished**, and you cannot estimate costs for, schedule, release, or start the production order.
    

    > [!NOTE]
    > <P>If you clear this check box, a worker must report the production as finished. This procedure is required even if the production is reported as finished when feedback is reported. For more information, see <A href="report-production-orders-as-finished.md">Report production orders as finished</A>.</P>



12. Select the **Accept error** check box if you do not want to receive an error log if inconsistencies occur in the production process, such as inconsistencies in the number of items produced or in the raw materials that are delivered for production. Clear the check box to receive an error log. The following issues are validated in the error log:
    
      - The quantity that is reported as finished is less than or equal to the quantity that was started on the production order.
    
      - All operations in the production route have been reported as finished.
    
      - All estimated materials have been delivered.
    
      - The quantity that is reported as finished for the production order equals the quantity that is reported as finished for the last operation in the route.

Back to top

## Set up production parameters for validating quantities

In the **Quantity validation** area, various limits and validation parameters can be set up to reduce the risk of erroneous data being entered about the start and completion of a production order.

1.  Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**.

2.  In the **Production parameters** form, in the **Quantity validation** area, in the **Maximum report quantity** field, enter a limit for the quantity of items that can be reported as finished on an operation or a job. This makes sure that only valid quantities are entered when workers provide production feedback.

3.  Select the **Validate startup quantities** check box if you want to add startup validation parameters to the process jobs of a production order.
    
    This check box is available only if **Status + quantity** is selected in the **Update start on-line** field in the **Start** area of the form.

4.  If you selected the **Validate startup quantities** check box, do the following:
    
    1.  In the **Startup validation method** field, select the validation method that you want to use to validate the started quantity on a process job.
    
    2.  Select the **Accept startup deviation** check box to allow deviation in the started quantity on a process job compared to the quantity that is allowed by the selected startup validation method.
    
    3.  In the **Accepted deviation in percentage** field, enter the percentage of excess quantity to allow for when you start a process job. This field is available only if the **Accept startup deviation** check box is selected.

5.  Select the **Validate feedback quantity** check box if you want to add quantity validation parameters to the process jobs of a production order.

6.  If you selected the **Validate feedback quantity** check box, do the following:
    
    1.  In the **Feedback validation method** field, select the validation method that you want to use to validate quantity feedback on process jobs.
    
    2.  Select the **Accept surplus production** check box if you want to accept a surplus in the feedback quantity on process jobs compared to the quantity that is allowed by the selected feedback validation method.
    
    3.  In the **Accepted surplus in percentage** field, enter the percentage of surplus quantity that you will allow when quantity feedback is registered on process jobs. This field is available only if the **Accept surplus production** check box is selected.
    
    4.  Select the **Accept production shortage** check box if you want to accept a shortage in the feedback quantity on process jobs compared to the quantity that is allowed according to the selected feedback validation method.
    
    5.  In the **Accepted shortage in percentage** field, enter the percentage of shortage that you will allow when quantity feedback is registered on process jobs. This field is available only if the **Accept production shortage** check box is selected.

Back to top

## Configure a form for registrations

You can use preconfigured registration forms for manufacturing execution. But you can also create new registration forms to meet business needs.

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Terminals** \> **Configure registration forms**.

2.  In the **Configure registration forms** form, click **New** to create a new configuration.

3.  In the **Configuration** field, enter a name for the new form.

4.  In the **Action Pane** field, click the arrow, and then, in the **Action Pane configuration** field, select a configuration.
    

    > [!TIP]
    > <P>An <STRONG>Action Pane</STRONG> contains tabs and buttons. You can configure the <STRONG>Action Pane</STRONG> to specify the buttons that are available on each tab. Click the <STRONG>Setup of Action Pane</STRONG> button to open the form where you can modify the <STRONG>Action Pane</STRONG>.</P>



5.  On the **General** FastTab, in the **Start page** field, select which jobs should be displayed when the worker opens the registration form.

6.  If the registration form will be used for registration on production jobs, in the **Feedback input method** field, select the layout of the report feedback form. Select from the following options:
    
      - **Grid** – When a worker reports feedback on production jobs, the **Report feedback** form opens, and the worker can report feedback on the active production jobs in a list.
    
      - **Wizard** – When a worker reports feedback on production jobs, the **Update feedback** form opens, and the worker can report feedback on the active production jobs one by one in a wizard.

7.  Select the **Disable close** check box if you do not want workers to close the registration form by using the standard buttons in Microsoft Dynamics AX. If this check box is selected, the registration form can be closed only by pressing CTRL+Q.

8.  Select the **Report quantity at clock-out** check box if you want workers to be prompted to report feedback when they make a clock-out registration.

9.  Select the **Job list check** check box if you want the system to verify that the job is included in the job list that is currently displayed on the screen.
    

    > [!TIP]
    > <P>This field is used to determine whether a worker can start jobs that are not displayed in the worker’s job list. This is relevant only when jobs are started by using a scanner. This job list check makes sure that a worker does not accidentally start a job that he or she should not be working on.</P>



10. Select the **Lock employee** check box to lock the worker identification in the **Job registration** form.
    

    > [!TIP]
    > <P>If this check box is selected, only one worker can use the registration terminal. The worker is not asked to log on again if no activity occurred in the <STRONG>Job registration</STRONG> form during a period of time. If another worker must make registrations on the terminal, the worker who has access to the <STRONG>Job registration</STRONG> form must click the <STRONG>Switch user</STRONG> button to give the other worker access to the <STRONG>Job registration</STRONG> form.</P>



11. Select the **Prompt for production area** check box if the worker must always select a production unit, resource group, and resource before opening the registration form.

12. On the **Appearance** FastTab, in the **Show messages** and **Show status** fields, select the layout of those areas in the registration form.

13. In the **Show preview** field, select the preview layout.

14. In the **Indirect activities**, **Production**, and **Project** fields, select the configuration to display for these job types in the job list in the registration form.
    

    > [!TIP]
    > <P>If you want to change the grid configurations or create a new grid configuration, click the <STRONG>Setup of grids</STRONG> button to open the <STRONG>Setup of grids</STRONG> form.</P>



Back to top

## Connect a worker to a specific registration form

You can select a specific registration form configuration for a worker. The selected configuration is displayed every time the worker logs on to the **Job registration** form.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Time registration workers**.

2.  In the **Time registration workers** list, double-click the worker.

3.  In the **Worker** form, in the left pane, click the **Employment** link. Then, on the **Time registration** FastTab, in the **Configuration** field, select the registration form configuration that the worker will use.

Back to top

 

## Set up allocation keys for bundling jobs

Allocation keys are used if a worker works on several production jobs at the same time during a work day. This is referred to as job bundling. The total time that is used on a bundle of jobs must be divided among the jobs according to an allocation key. Allocation keys can be set up for a site, a production unit, or a resource.

To learn more about the different allocation keys, and to view examples of how to use allocation keys to calculate time, see [About allocation keys](about-allocation-keys.md).

1.  Click **Production control** \> **Setup** \> **Production** \> **Allocation keys**.

2.  In the **Allocation keys** form, click **New** to create a new allocation key.

3.  In the grid, select a site, a production unit, or a resource.

4.  In the **Bundle type** field, select the allocation key that you want to use.


> [!NOTE]
> <P>In the <STRONG>Production parameters</STRONG> form, in the <STRONG>General</STRONG> area, in the <STRONG>Bundle type</STRONG> field, you can select the allocation key to use by default when allocation keys are not specified.</P>



Back to top

## Find form help

[Manufacturing execution production parameters (form)](https://technet.microsoft.com/en-us/library/hh208822\(v=ax.60\))

[Time and attendance parameters (form)](https://technet.microsoft.com/en-us/library/aa634266\(v=ax.60\))

[Configure registration forms (form)](https://technet.microsoft.com/en-us/library/aa616991\(v=ax.60\))

[Allocation keys for bundled jobs (form)](https://technet.microsoft.com/en-us/library/aa586345\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

## Find related tasks

[Setting up time registration for workers](setting-up-time-registration-for-workers.md)

[Set up and apply piecework in production](set-up-and-apply-piecework-in-production.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

