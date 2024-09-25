# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)| [Labour Transfer](#labour-transfer) | [Send Dcument](#send-document) |


<br>
<br>


# [**Labour Cases**](#lodging)

| [Rest Stage](#rest) | [Refuse To Work Stage](#refuse-to-work) | [Dead Stage](#dead) | [Jail Stage](#jail) | [Hospital Stage](#hospital) | [Escape Stage](#escape) |

<br>

## [**Rest**](#labour-cases)

 Rest Transaction will creates with Sub-Category from different sources.

- **Rest Process will start based on sub-category as follows:**

   - ****Reserved For VIP***

     - Process starts with Reserved for VIP stage.
     - Employee status changed to "**Reserved For VIP**".


    - ****Reserved For Sales***

       - Process starts with Reserved for Sales stage.
       - Employee status changed to **Reserved For Sales**


    - ****Other Sub-Category***

      - Process starts with ***New*** stage.
      - Employee status changed to **Rest**.

<br>

### [***Rest Workflow:***](#rest)

- ### New:

  - Newly initiated Request is moved to Rest or Reserved for VIP stage.

  - **User can move to following stage.**

       * _In The Action fields are Following:_

         ***1.Rest*** - User Complete and move to **Rest** stage.

         ***2.Reserved For VIP*** - User complete and move to *Reserved For VIP* status.

- ### Rest:

  - **User can move to following stage.**

     *  _In The Action fields are Following:_

        ***1.Reserved For VIP*** - User complete and move to **Reserved For VIP** status

        ***2.Waiting For Action*** - Usercomplete and moved to **Waiting for Action** stage

- ### Reserved For VIP:

  - In this stage, Employee status changed to as **Reserved for VIP**.

  - Complete - Waiting for Action, And Employee status changed to as **Rest**.

   - **User can move to following stage.**

     * _In The Action fields are Following:_

       **1.Complete** - Complete and Moved to **Waiting for Action** stage.


- ### Reserved For Sales:

   - Employee status changed to as **Reserved for Sales**.

   - Complete - Waiting for Action, Employee status changed to as **Rest**.


- ### Waiting For Action:


  - If Employee moved to "**Ready to work**" then employee status changed to **Ready to work** category.

  - If Employee ***"Refuse to work"*** then Investigation process will start for the Employee and status changed to **Rufuse to Work** category.

  - If Employee request for Vacation, Then Leave Request will create for with Required Data if Employee eligible.

  - If Employee request for Retirment(Final Exit), then retirement request will create for Employee with required data.

  - **User can move to following stage.**

    * In The Action fields are Following:

       ***1.Ready to Work*** - User complete and move to process with Required stage.

       ***2.Refuse to Work*** - User complete and move to process with **Refuse To Work** stage.

       ***3.Leave*** - User coomplete and move to process with **Leave Request** stage.

       ***4.Final Exit*** - User complete and move to process with **Retirement** stage.


<br>
<br>

## [**Refuse to Work**](#labour-cases)

Transaction will creates with Sub-Category in different sources.

  - **Refuse to Work Process will start based on Return Reason (sub-category) as follows:**

     - **Request For Vacation:**

       - If Employee refuse to work and request for vacation after return, then Process starts with **Waiting For vacation** stage.

       - Then Employee status changed to **Waiting For vacation**.

     - **Request for Exit:**

       - If Employee refuse to work and request for Exit / Retirement after return, then Process starts with **Waiting For Exit** stage.

        - Then Employee status changed to **Waiting For Exit**.

     - **Other Subcategory:**

       - Process starts with **Under_Investigation** stage.

       - Employee status changed to **Under_Investigation**.

<br>

### [***Refuse to Work - Workflow:***](#refuse-to-work)

- ### Under Investigation:

    - User can move to following required stage,

       ****Refuse to Work,**

       Moved to Waiting for Action and then **Investigation process** will start for Emloyee.

      *****Ready to Work,***

       Moved to Required stages, and then employee status changed to **Ready to work**.

    - **User can move to following stage.**

       * _In The Action fields are Following:_

          *  **1.Refuse to Work** - Complete and Moved to **Refuse to Work** stage.

          *  **2.Ready To Work** - Complete and Moved to **Complete** stage.

- ### Refuse to Work:

  * Investigation process will start for Employee,

  * If Employee Refuse to Work and then Investigation process will start.

  * If Employee is Ready to work, then employee status changed to Ready to work.

  * If Employee is request for Vacation, then leave request will create with required data for Employee.

  * If Employee rquest for Final Exit, then Retirement request will create with required data for Employee.

   - **User can move to following stage.**

     * _In The Action fields are Following:_

       * **1.Final Exit -** Complete and Moved to process **Retirement request** stage.

       * **2.Vacation -** Complete and Moved to process **Leave Request** stage.

       * **3.Refuse To Work -** Complete and move to start with **Under Investigation** stage.

       * **4.Ready To Work -** Complete and Moved to Required stages.


- ### Legal Action:


- ### Waiting For Vacation:

   - Waiting for this stage to complete the process for Employee,
 with **Leave** Request or **Retirment** Request for Employee.

   - Once complete the Leave/Retirement Process for employee, and this stage complete with system integration.

- ### Waiting For Exit:

    - Once Employee Exit completed then this stage complete with Employee Exit status.

<br>
<br>

## [**Dead**](#dead)

In Case of Employee is deceased, then Employee Status is Changed to **Dead**.

<br>

### [***Dead Workflow:***](#dead)

- ### Request:

  - In this stage, Required to register the Information about Employee Death into Portal, as Labour ID, Location and Date while Death.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** - Death reason or Any Information.

    * ***Location*** - Employee being which place to Locate while Death.

    * ***Date*** - Actual Date of Employee Death.


  - If "Employee Worked with customer", Then Required to **end the contract** with Customer beacause of the Employee Deceased.

  - If "Employee is on Lodging", then **Checkout** process will stat for Employee from the Lodging.

  - **User can move to following stage.**

     * _In The Action fields are Following:_

        **1.Complete** - Complete and Moved to **Action** Stage.

- ### Action:

  - And then **Final settlement** will create in **Retirement** request, for Employee after Registered Dead in Portal .

  - Retirement will create, When Employee is deceased in Lodging and Working status.

  - In this stage, Request is move to **Complete** stage.

  - **User can move to following stage.**

     * _In The Action fields are Following:_

       * **1.Complete** - Moved to Complete stage.

<br>
<br>


## [**Jail**](#labour-cases)

 In This stage, The Employee status is Changed to **Absent**.

   - If employee is working with customer, Then Required to end the contract with Customer.

   - And If employee in lodging, Then checkout process will start for Employee from the lodging

<br>

### [***Jail Workflow:***](#jail)

- ### Request:

  - Required to register the Information into Portal, about Employee while send to Jail, as Labour ID, Location and Date while Death.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** -  Reason or Additional Information.

    * ***Location*** - Employee Located place.

    * ***Date*** - Actual Jailing Date of Employee.

  - **User can move to following stage.**

       * _In The Action fields are Following:_

          **1.Complete** - Complete and Moved to **Action** stage.


- ### Action:

    - If The Employee is **Return** from Jail, Then Check-in process will start for the Employee. Once the **Checkin** is Completed for Employee then Moved to Completed stage.

    - If Employee Reqested for the **Vacation**, Then **Leave Request** process will start for Employee.

    - or The Employee terminated and moved to **Final Exit**, Then **Retirement** request will create for the **Final Settlement** to Employee.

    - **User can move to following stage.**

      * _In The Action fields are Following:_

         **1.Vacation** - Complete and Move to **Leave Request** Stage.

         **2.Final Exit** - Complete and Move to **Retirement/Final Exit** stage.

         **3.Return** - Complete and moved to **Return to Work** status.

<br>
<br>

## [**Hospital**](#labour-cases)

In This stage, Employee status is changed to **Sick**.

- And If Employee working with Customer, Then required to End the Contract with Customer.

<br>

### [***Hopital Workflow:***](#hospital)

- ### New:

  - Required to register the Information into Portal, about Employee while request for Hospital/Sick, as Labour ID, Location and while admitted to Hospital.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** -  Reason or Additional Information.

    * ***Location*** - Employee Located place while request for Sick.


   - **User can move to following stage.**

     * _In The Action fields are Following:_

        **1.Sent to Hospital** - Complete and Moved to **Sent to Hospital** stage.

        **2.Sick Leave** - Complete and moved to **Sick Leave** stage.

        **3.Waiting for Action** - Complete and Moved to **Waiting For Action** stage.

- ### Sent to Hospital:

   - In this stage, **User can move to following required stage,**

     * _In The Action fields are Following:_

       **1. Admitted to Hospital** - Complete and move to **Admitted to Hospital** stage.

       **2. Sick Leave** - Complete and move to **Sick Leave** stage.

- ### Admitted to Hospital:


  - When Admitted to Hospital stage is starts, then checkout process will start for Employee from lodging.

  - When Employee return from the Hospital, then checkin will start to lodging, and move to required stage.

  - **User can move to following stage.**

     * _In The Action fields are Following:_

       **1.Sick Leave** - Complete and moved to **Sick Leave** stage.

       **2.Waiting for Action** - Complete and moved to **Waiting for Action** stage.


- ### Sick Leave:

   -  If Employee request for Sick Leave, then Will start process for Sick Leave.

  - **User can move to following stage.**

      * _In The Action fields are Following:_

         **1.Waiting for Action** - Complete and moved to **Waiting for Action** stage

- ### Waiting for Action:

   - In this stage, investigate the Employee after return to Lodging,

       And User can moves to required stages as follows.

       - ***Ready To Work,***

          Employee status will changed to _Ready to Work_, And moved to required stage.

        - ***Refuse To Work,***

          Employee status will changed to _Refuse to Work_, And moved to required stage.

      - ***Send To Hospital,***

         Employee status will changed to _Send To Hospital_, And moved to required stage.

     - **User can move to following stage.**

         * _In The Action fields are Following:_

           **1.Ready to Work** - Complete and moved to **Complete** stage

           **2.Refuse to Work** - Complete and moved to **Complete** stage.

           **3.Sent to Hospital** - Complete and moved to **Send To Hospital** stage.

<br>
<br>

## [**Escape**](#labour-cases)


- In this stage, Escape request will created from **individual** module or by user.

- Employee status is changed to **missing-missing** status.

   - ****Employee status after 10 Days**,

     - After 10 days of Employee missing, then employee will moved to **Escaped stage** by system schedule.

     - Employee status changes as ***Missing-Escaped***.

     - And User also can do manual action on this process.

   - ****Employee status after 20 Days**,

     - After 20 days of Employee Missing,  then employee will moved to **Registered In MOL** stage by system schedule.

     - And then Employee status changes as ***Escaped-Escaped***.

     - And user also can do manual action on this process.

<br>

### [***Escape Workflow:***](#escape)


- ### Missed:

  * In this stage, Required to register the Employee  Information into Portal, about Employee details related to Escape, as Labour ID, Escape Date, Remarks, Escape Point and Uploading file via Choose File.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Escape Date*** - Employee Escaped Date.

    * ***Remarks*** - Reason or Additional Information.

    * ***Escape Point*** Exact place of Employee Escaped.

    * ***Choose File*** Uploading the file related to Employee.

    <br>

   - And In this stage, Waiting for Employee return within 10 days, and After 10 days of Employee Missing, and Employee will moved to **Escaped stage** by system schedule.

   - And Employee status changes as ***Missing-Escaped***.

   - And User also can do manual action on this process.

  - **User can move to following stage.**

       * _In The Action fields are Following:_

           **1. Complete** - Complete and Moved to **Escaped** stage.

           **2. Escape Return** - Complete and Moved to **Return from Escape** stage.

           **3. Jail** - Complete and Moved to **Complete** stage.

- ### Escaped:

   - In This stage, Waiting Employee return  within @0 days, After 20 days of Employee Missing,  and employee will moved to **Registered In MOL** stage by system schedule.

   - And Employee status changes as ***Escaped-Escaped***.

   - And user also can do manual action on this process.

   - **User can move to following stage.**

       * _In The Action fields are Following:_

           1. **Complete** - Complete and Moved to **Register in MOL** Stage.

           2. **Escape Return** - Complete and Moved to **Return from Escape** Stage.

           3. **Gov_Case** - Complete and Moved to **GOV_Case** Stage.

           4. **Deport** - Complete and Moved to **Deport** Stage.



- ### Gov Case:

     * **And then User can move to required stage,**

        * _In The Action fields are Following:_

            1. **Move to Escape** - Complete and moved to **Escaped** stage.

- ### Deport:

   - In this stage, Employee status changed to **Deport-Missing** status,

   - If the Employee will deported then **Retirement** request will create for **Final settlement** to Employee.


- ### Register in MOL:

   - In This stage, Employee status changes to **Escaped-Escaped** status.

   - If the Employee return from Escape, then moved to **Return from Escape** stage.

   * **And then User can move to required stage,**

        * _In The Action fields are Following:_

             1. **Complete** - Completed and Moved to **Complete** stage.
            
             2. **Escape Return** - Complete and Moved to **Return From Escape** Stage.

             3. **Move to Gov_Case** - Complete and Moved to **Gov-Case** stage

- ### Return From Escape:

  - If Employee returned to Customer from Ecape Return, Then Employee status changed to **working-withcustomer** status.

  - If Employee return to lodging, Then **check-in request will** creates for Employee.

  - Once the checkin request complete for Employee, Then moved to **complete** stage.

  - And then this process will skip and move to **completed** stage.

   * **And then User can move to required stage,**

        * _In The Action fields are Following:_

           1. **Complete** - Complete and Move to **Escape Cancelled** Stage.


- ### UnRegister Muqeem:

  - After Employee return from Escape, if the employee already R***egister in MOL***, then this stage starts for Employee.

  * A**nd then User can move to required stage,**

      * _In The Action fields are Following:_

          1. **Complete** - Complete and Moved to **Escaped Cancelled** stage.

- ### Escaped Cancelled:

   If the Employee return from Escape,

<br>