# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)| [Labour Transfer](#labour-transfer) | [Send Dcument](#send-document) |

<br>


> ## Send Document

* Send the Document to employee, who stayed in Customer place or Lodging by Branch.

* Send Document have two type of flow based on employee type
in delivery process document will called as **envelope**.

<br>

## **Individual:**

<br>

## *Envelope:*

### **Individual Envelope**:

 * Envelope will process by individually.

 * when "Put in Envelope" stage started in related process, envelope will create in Waiting stage.

 * In Lodge setup have "DocumentBranch" field to setup Document branch(which handled the delivery).

 * All envelope will sent to Riyadh Lodging Branch by default Branch.

 * When Envelope created system will update "source branch" as default Branch.

 * Employee stayed (Lodging or Customer) document branch called as "Prefered Document Location".

### **Envelope Movement**

- To Transfer the envelope to another branch by From and To Branch details.

- It is the history for envelope movement.

<br>

## Individual - WorkFlow:

- ### Waiting:

  - When user complete the "**Put in Envelope**" stage, it will move to Sent to Branch stage.

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Send To Branch** Stage.



- ### Sent To Brance:

  - If employee Prefered Document Location is same as  envelope source branch. process will moved to Waiting for delivery.

  - If employee Prefered Document Location not same as  envelope source branch, Sent to Branch stage started and Envelope movement will created for the envelope

  - User will move to **Received in Branch** stage.

    - **Envelope movement will created for the envelope as following:**

      - From Branch as envelope Source Branch
      - To Branch as employee Prefered Document Location

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Receive In Branch** Stage.

        ***2.Lost*** - Complete and moved to **Lost** Stage.


- ### Receive in Branch:

   - User will receive the envelope and confirm by Action.

   - Process will move to Waiting for Delivery.

   - Envelope source branch will update as movement destination branch.

   - If document lost, process will move to Lost stage.

   - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Waiting For Delivery** Stage.

        ***2.Lost*** - Complete and moved to **Lost** Stage.

- ### Waiting For Delivery:

   - Customer will Notify about document by sms with location.

   - If document delivered, User will move it to the Completed stage,

   - If Employee moved to another location, Sent to Branch stage will start to transfer the document.

   - If document lost, process will move to Lost stage

   - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Complete** Stage.

        ***2.Lost*** - Complete and moved to **Lost** Stage.

        ***3.Resume*** - Complete and moved to **Send To Branch** Stage.

- ### Lost:

  - User can make resume action, to move envelope to Sent to Branch stage.

  - User will make action, Lost to move to process to completed stage with lost status.

  - **Then User will move the Process to required stage.**

     *  _In The Action fields are Following:_

        ***1.Resume*** - Complete and moved to **Send To Branch** Stage.

        ***2.Lost - Move To Complete*** - Complete and moved to **Complete** Stage.


<br>
<br>

## **Business:**

<br>

## *Package:*

- **Business Employee** document will deliverd by **package** flow.

- Package contains package Lines with envelope details.

- When "**Put in Envelope**" stage started in related process, envelope will create stage and status in Waiting status

- Envelope will for **Iqama** and **ATM** process to gether, if both package completed, then only it will added to the package.
for other process, once "**Put in Envelope**" completed, it will added to the package.

- When user complete the "Put in Envelope" stage, system will any open package the employee contract.

- **If open package found, it will created package line for the open package**

- **If open package not found, it will create new package for employee contract and add package Lines with Open status**

<br>

## Package - Workflow:

- ### Open Package:

   - User will move to the Closed - Un-Preparation stage.

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Closed - Under Preparation** Stage.

        ***1.Hold*** - Complete and moved to **On Hold** Stage.

- ### Closed - Under Preparation:

  - User will move to the Dispatching stage

     *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Dispatching** Stage.



- ### Dispatching:

  - Process will move to **Dispatched & Waiting for Confirmation** stage.

    *  _In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Dispatched & Waiting for Confirmation** Stage.


- ### Dispatched & Waiting for Confirmation:

  - User can partially or delivered all envelope by selecting the envelope.

  - Un-selected envelope will move to the Open packaged.

  - Process will move to complete stage.

     * In The Action fields are Following:_

        ***1.Complete*** - Complete and moved to **Complete** Stage.


<br>

## *Move Envelope:*

- List to View the all **Open Envelope**.

- User can move the one **Envelope** to **Exisiting Package** or **New Package**.

- User can take action on Packages,

     * _In The Action fields are Following:_

        ***1.Move to Auto*** - The Package will Move without take on any Action.

        ***2.New Package*** - User will create the **New Package**, from any **Existing package**.

        ***3.Existing Package*** - User Will add the **New Package** to Any **Existing Package**.

<br>


<br>
