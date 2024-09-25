# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)|

<br>

# [Labour Movement](#lodging)

| [Labour Check-in](#labour-check-in) | [Labour Check-out](#labour-check-out-request) |

## [**Labour Check-in:**](#labour-movement)

When Ever Employee returned to Lodging, from below Listed category will start the Checkin process manually or start and complete by system integration.


### **In Check-in**:

   The Checkin request will create from the following sources.

  - _**Employee Arrival**_,

      When New Employee arrived to Lodging, Lodging Checkin will create without Request.

 - _**Return from Customer \ In Contract \ From Business**_,

     Checkin will start for Employee from Contract, When Employee return from contract.

 - _**Vacation Return**_,

     Checkin created from Employee Vacation Request, After Employee returned from on Vacation.

 - _**Escape Return \ Labour Transfer**_,

     Checkin will create based on Labour Transfer, If the Employee tranfered to other organization and Return to Lodging.

     Checkin will created, when Employee return after Escaped from Lodging or customer.

 - _**Jail Return \ Hospital Return**_,

      If Employee returned from Jail or Hospital, then Checkin will create without End the Contract.

 - _**Business**_,

      Request will created from CheckIn Request for business employee who already end from contract.(status will be "Waiting For Action")

<br>

### ***Workflow Stages in Labour Check-In***


- ### Requested:

   - Checkin request will move to _**"Waiting For Action"**_ from Requested.

   - User can cancel the checkin request to Employee,  When the checkin type of Employee is **"CheckIn_Without_End_Contract"**.

  - **User can move to following stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Waiting For Check-in** Stage.

        ***2.Reject*** - Complete and moved to **Cancel** stage


- ### Waiting For Check-in:

   - Check-in Request will created for "Business Employee", who already **"End from Contract"** in Business.

   - The Check-in Request will create with Current Date.

   - In this stage, Employee Status is changed to "Waiting For Action-Lodging".

<br>

   - **Once Check-in created for Employee, will update following action based on check-in types:**

      - _**End the Employee from on contract**_

         - _**Return From Customer**_, - Check-in will created, If the Employee Return from Customer and End the Employee from contract.

         - _**From Business**_, - Check-in will created, If the Employee Return from Business and End the Employee from contract.

         - _**In Contract**_, - Check-in will created from Contract, When Employee return from on contract and End from the contract.


      - _**And process will move to Required stages**_

         - _**Vacation Return**_, - Checkin will created from Employee Leave Request, when Employee return from Vacation and then move to Required stage.

         - _**Escape Return**_, - Checkin will created, when Employee return after Escaped from Lodging or customer and then move to Required stage .

         - _**Jail Return**_, - Checkin will created, when Employee return from Jail to Lodging and then move to Required stage .

         - _**Hospital Return**_, Checkin will created, when Employee return from Hospital to Lodging and then move to Required stage.

         - _**Labour Transfer**_, Checkin will create based on Labour Transfer, when Employee Return to Lodging for Transfer and then move to Required stage.

     - **User can move to following stage.**

       *  _In The Action fields are Following:_

          ***1.Complete*** - Complete and moved to **Update Worker Status** Stage.

          ***2.Reject*** - Complete and moved to **Cancel** stage


- ### Update Worker Status:

  - Once Checkin is created for Employee, then user will start the process for Employee to Lodging.

  - If Employee Return from Labour Transfer, then this stage will skip and Employee Status is Changed to _**"Prev Employee Status"**_.

  - When Complete the status user will select the "**Return Reason**" and "**Sub Category**"

  - Based on Return Request Employee status and process will start.

     - _End of Contract_

       - Once Employee End the contract with cutomer then Employee Status updated to "**Ready To Work**".

     - _Request Vacation_

       - Employee Require for Vacation, Investigation Process will start with Request Vacation.

     - _Request For exit_

       - Employee Require for Exit, and then Investigation Process will start with Waiting For Exit.

     - _Customer from Customer_

       - Employee Require for Exit, Investigation Process will start with Investigation.

     - _Complaint from Employee_

       - If Employee Complaint on Customer and, Investigation Process will start with Investigation to Employee.

     - _Sick_

       - If Employee want to treatment then Hospital process will Start.

     - _Rest_

       - If Employee required for Rest, the rest Process will start.

  - And then the process will moved to confirmed stage.

  - **User can move to following stage.**

       *  _In The Action fields are Following:_

          ***1.Complete*** - Complete and moved to **Confirmed** Stage.

          ***2.Reject*** - Complete and moved to **Cancel** stage


- ### Confirmed:

   - In this stage, The process will moved to required stage.

- ### Cancel:

   - Process moved to cancel stage, once the request is cancelled from stage.

<br>

## [**Labour Check-Out Request:**](#labour-movement)

- ### **Check-out Request will create by following source.**

  * When Employee will delivered to customer, and same time check-out will create for Employee with based on contract.

  * If Employee, delivered to customer, then check-out will create for Employee with based on contract.


  * Check-Out will create automatically with system integration, When Employee will Return from On Vacation.

  * Check-Out will create automatically with system integration, when Employee is Escaped from Customer or Employer on contract.

  * System Integration will create the Check-Out process for Employee, When Employee request for Retirement.

  * When Employee on Transfer, then Check-Out process will create with System Integration automtically.



  * Check-Out will create for Employee with system integration, When the Employee is return from the Hospital.

  * Check-out will Create from Labour Transfer with system integrtion, when Employee return from Labour Transfer.

<br>

### ***Check-out Workflow stages:***

- ### Requested:

  - The newly required request will move to process into ***Waiting For Check-out*** stage.

   - **User can move to following stage.**

       *  _In The Action fields are Following:_

          ***1.Complete*** - Complete and moved to **Waiting For Check-Out** Stage.



- ### Waiting For Check-out:

  - When complete this stage, checkout date updated with current date.

  - Employee status will changed based on checkout type.

  - ___Once check-out updated for Employee, then will update the following action, based on checkout type.___

    - If The Employee delivered to Customer, then the process will complete with required stage.

    - If The Employee delivered to Business, then the process will complete with required stage.

    - When Labour Transfer is completed, then the process moved to required stage.

    - When Employee return from Hospital, Then process will moved to required stage.

    - **User can move to following stage.**

       *  _In The Action fields are Following:_

          1.**Complete** - User Will complete or Move the process with Required stage.
