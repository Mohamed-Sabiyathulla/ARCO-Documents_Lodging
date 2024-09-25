# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)| [Labour Transfer](#labour-transfer) | [Send Dcument](#send-document) |

<br>

> ## Labour Transfer

| [Transfer Order](#transfer-order) | [Transfer Request](#travel-request) |

<br>

## Transfer Order:


- In Labour Transfer, make Employee transfer to any other lodging from one Employee check-in Lodging.

- The Transfer order create with to Location.

- In this stage, Transfer order Creation is including with necessary information for new order creation, these all information is to be used for Transfer Order creation:

    * ***Transfer Order ID*** - Once Required Data Updated for New Order Creation, Then transfer ID will create for this transaction.

    * ***Transfer Reason*** - Transfer Reason or Any Other Additional Information.

    * ***To Location*** - Employee being which location to Transfer.

    * ***Total Labour*** - Required labours in numbers.

    * ***Request Date*** - Actual Transfer request creation Date.

    * ***Required Date*** - Actual Required Date for Labours.

<br>

## Transfer Order - Workflow:


User can edit and modify the "**Transfer Order**" Details.

- ### Requested:

  - **In this stage, User will create the "'Transfer Lines'" with information required as below:**

    - ***Profession***,
    - ***Quantity***.
    - ***Nationality***,
    - ***Gender***.

   - **Then ser will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Process** Stage.

        ***2.Cancel*** - Complete and moved to **Cancelled** Stage.

- ### Process:

   - User will assign the employee to transfer line.

   - Once user Assigned the Employee, then Transfer Request will started.

   - And User can close the transfer .

   - Once order closed cannot assign any employee on this Transfer.

   - **Then user will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Move To*** - Complete and moved to **Complete** Stage.


- ### Complete:

In this stage, Completed request used to track the status of the request and Information.

- ### Cancelled:

In this stage, Canceled request used to track the cancel reason, status of the request and Information.


<br>
<br>

## Transfer Request:

User can create Internal Transfer for Branch Lodging with out Transfer order

<br>

## Transfer Request - Workflow:

- User can Create the Internal Tranfer with Employee.

  * **Internal Transfer will create with following information**:

     * **Select Employees**,

       Selecting with seperate employee with marking the Grid view of Employee.

        * *Employee Selection as Follows*:

           **"Selected Employees" - Count of Employee for Transfer in Numbers.*
           
           **"Required Location" - Required Place to Employee Transfer.*
           **"Comments" - Any Information and Transfer Reason.*

     * **Select from Lodging**,

         To Selecting the Lodging Location.

     * **Age**,

         For selecting, to required Age group of Employee.

     * **Gulf Experience**,

         For selecting the Employee, with related Work experienced in Gulf.

     * **Total Experience**,

        Selecting the Employee, with Total Work Experienced.

     * **Employee List**,

        Advanced Search with Employee Information,

            *Employee ID, Name, Iqama Number, Passsport Number, Mobile Number and Border Number.

<br>

- ### Travel Request:

  - User will move to check-out in current lodging stage

   - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Checkout in Current Lodging** Stage.

        ***2.Cancel*** - Complete and moved to **Cancelled** Stage.


- ### Check-Out In Current Lodging:

  - Check-out request will create with check-out type-Transfer

  - Once check-out request completed, employee check-out from current lodging  and process will move to Travelled stage

  - **Employee status will changed to In-transit**

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Travelled** Stage.

- ### Travelled:

  - User will move to Check-InBranch Lodging stage.

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Check-In Branch Lodging** Stage.

- ### Check-In Branch Lodging:

  - Check-In request will create with check-In type-
  
  - Once check-in request completed, employee check-in to Transfer order lodging  and process will move to Arrived stage

  - **Emplloyee status will changed to Prev Status last lodging of the employee**

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Arrived** Stage.


- ### Arrived:



- ### Cancelled:

    In this stage, moved the Cancelled requests.

<br>
