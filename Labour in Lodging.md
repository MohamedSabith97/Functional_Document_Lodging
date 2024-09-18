# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)|

# Labour in Lodging

| [Labour in Lodging](#labour-in-lodging-1) | [Labour in Marketing](#labour-in-marketing) | [Lodging Profile Search](#lodging-profile-search) | [Ind Sales Profiles](#ind-sales-profiles) |


## **Labour in Lodging:**

Labour in lodging is a status view, and List to view the number of employees in lodging with work category wise.

And Take action to create ID Card for employee.

And Use to take printout as below List for Employee, as like

      * Food Report,
      * Temporary Iqama,
      * New Arrival request,
      * Check in and Check Out.

 - Intituitional Quarantine - Employee status as Intituitional Quarantine, updated from New Employee request.

 - Under Documentation - Employee status as Under Documentation, updated from New Employee request.

 - Under Training - Employee status as Under Training, updated from New Employee Request.

 - Waiting For Action - Employee status as Waiting For Action, updated from New Employee Request.

 -  Reserved For VIP - Employee status as Reserved For VIP, updated from New Employee Request.

 - Refuse to Work - Employee status as Refuse to Work, updated from New Employee Request.

 - Ready to Work - Employee status as Ready to Work, updated from New Employee Request.

 - Booked - 

 - In transist - 

 - Vacation Requested - Employee status as Vacation Requested, updated from Employee Leave Request.

 - Final Exit requested - Employee status as Final Exit requested, updated from Employee Retirement.

Waiting For TravelFinal Exit requested, updated from (Employee Leave Request or Employee Retirement).

<br>

## **Labour in Marketing:**

List to view the Employees status information with who are waiting for **"Ready to Work"** status.

Tracking purpose for Employee status with Lodging Locations.


- In require to take on Action as:

   * **_Investigation_**

      Process will start for Employee to send for Investigation.

   * **_Rest_**

      Process will start for Employee to send for Rest.

<br>

## **Lodging Profile Search:**

- User can view the Employee List as Card View, who resides in Lodging Locations.

- User can review the status and Information of Employee, with Advance Search.

- User can Reserve the selected Employees for a Short period.

   - User can Reserve the Employee for minimum 15 minutes. In spite of the Employee in **"Ready to work"** status.

   - And User can also extent the Reservation time period. If he required.

   - If User did Reservation on Employee profile, and Employee Profile status changed to as **"Reserved"**.


<br>


## **Ind Sales Profiles:**

- User can review, The List of Employee who are waiting in **"Ready to Work"** status.

- User can review the Information and status of Employee, with Advance Search.

- User can review the Employee profile information with Advance search.

- List to view the Employee profile, with ordered and sorted by Profile Minutes.

    - **"Profile Minutes"** - it will Calculate the Time period for every Employee profile status, since the profile listed into Sales Profile List.

    - Employee profile status will sorted list and order the Profile of lead Duration time in this Employee profile status.

    - Time calculation for Employee status are including  **"Ready to Work" status, "Booked" status, "Reserved" status.**

<br>
<br>
<br>


# Labour Movement

| [Labour Check-in](#labour-checkin) | [Labour Check-out](#labou) |

## **Labour Check-in:**

When Ever Employee returned to Lodging, from below Listed category will start the Checkin process manually or start and complete by system integration.

<br>

### **In Check-in**:

   The Checkin request will create from the following sources.

  - _**Employee Arrival**_,

      When New Employee arrived to Lodging, Lodging Checkin will create without Request.

 - _**Return from Customer \ In Contract \ From Business**_,

     Checkin will start for Employee from Contract, When Employee return from contract.

 - _**Vacation Return**_,

     Checkin created from Employee Vacation Request, After Employee returned from on Vacation.

 - _**EscapeReturn \ LabourTransfer**_,

     Checkin will create based on Labour Transfer, If the Employee tranfered to other organization and Return to Lodging.

     Checkin will created, when Employee return after Escaped from Lodging or customer.

 - _**JailReturn \ HospitalReturn**_,

      If Employee returned from Jail or Hospital, then Checkin will create without End the Contract.

 - _**Business**_,

      Request will created from CheckIn Request for business employee who already end from contract.(status will be "Waiting For Action")

<br>

### **Workflow Stages in Labour Movements**,


- ### Requested:

   - Checkin request will move to _**"Waiting For Action"**_ from Requested.

   - User can cancel the checkin request to Employee,  When the checkin type of Employee is **"CheckIn_Without_End_Contract"**.


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


- ### Update Worker Status:

  - Once Checkin is created for Employee, then user will start the process for Employee to Lodging.

  - If Employee Return from Labour Transfer, then this stage will skip and Employee Status is Changed to _**"Prev Employee Status"**_.

  - When Complete the status user will select the "**Return Reason**" and "**Sub Category**"

  - Based on Return Request Employee status and process will start.

     - End of Contract

       - Once Employee End the contract with cutomer then Employee Status updated to "**Ready To Work**".

     - Request Vacation

       - Employee Require for Vacation, Investigation Process will start with Request Vacation.

     - Request For exit

       - Employee Require for Exit, and then Investigation Process will start with Waiting For Exit.

     - Customer from Customer

       - Employee Require for Exit, Investigation Process will start with Investigation.

     - Complaint from Employee

       - If Employee Complaint on Customer and, Investigation Process will start with Investigation to Employee.

     - Sick

       - If Employee want to treatment then Hospital process will Start.

     - Rest

       - If Employee required for Rest, the rest Process will start.

  - And then the process will moved to confirmed stage.


- ### Confirmed:

The process will moved to required stage and confirmed with this stage.

- ### Cancel:

Process moved to cancel stage, once the request is cancelled from any stage.

<br>

## **Labour Check-out Request:**

### **Check-out Request will create by following source.**

* When Employee will delivered to customer, and same time check-out will create for Employee with based on contract.

* If Employee, delivered to customer, then check-out will create for Employee with based on contract.

<br>

* Check-Out will create automatically with system integration, When Employee will Return from On Vacation.

* Check-Out will create automatically with system integration, when Employee is Escaped from Customer or Employer on contract.

* System Integration will create the Check-Out process for Employee, When Employee request for Retirement.

* When Employee on Transfer, then Check-Out process will create with System Integration automtically.

<br>

* Check-Out will create for Employee with system integration, When the Employee is return from the Hospital.

* Check-out will Create from Labour Transfer with system integrtion, when Employee return from Labour Transfer.

<br>

### **Check-out Workflow stages:**

- ### Requested:

  - The newly required request will move to process into ***Waiting For Check-out*** stage.


- ### Waiting For Check-out:

  - When complete this stage, checkout date updated with current date.

  - Employee status will changed based on checkout type.

  - ___Once check-out updated for Employee, then will update the following action, based on checkout type.___

    - If The Employee delivered to Customer, then the process will complete with required stage.

    - If The Employee delivered to Business, then the process will complete with required stage.

    - When Labour Transfer is completed, then the process moved to required stage.

    - When Employee return from Hospital, Then process will moved to required stage.

      - In The Action fields are Following:

        ___1.Complete___ - User Will complete or Move the process with Required stage.


<br>
<br>


# **Labour Case**

### _**Rest**_

 Rest Transaction will creates with Sub-Category from different sources.

**Rest Process will start based on sub-category as follows:**

****Reserved For VIP***

   - Process starts with Reserved for VIP stage.
   - Employee status changed to "**Reserved For VIP**".

<br>

****Reserved For Sales***

   - Process starts with Reserved for Sales stage.
   - Employee status changed to **Reserved For Sales**

<br>

****Other Sub-Category***

   - Process starts with ***New*** stage.
   - Employee status changed to **Rest**.

   <br>


### ***Rest Workflow:***

- ### **New:**

  - Newly initiated Request is moved to Rest or Reserved for VIP stage.

       * _In The Action fields are Following:_

         ***1.Rest*** - User move to **Rest** stage

         ***2.Reserved For VIP*** - User move to *Reserved For VIP* status.

- ### **Rest:**

  - User can move to following stage.

     *  _In The Action fields are Following:_

        ***1.Reserved For VIP*** - User move to **Reserved For VIP** status

        ***2.Waiting For Action*** - User moved to **Waiting for Action** stage

- ### **Reserved For VIP:**

  - In this stage, Employee status changed to as **Reserved for VIP**.

  - Complete - Waiting for Action, And Employee status changed to as **Rest**
     * _In The Action fields are Following:_

       **1.Complete** - And Moved to **Waiting for Action** stage.


- ### **Reserved For Sales:**

   - Employee status changed to as **Reserved for Sales**.

   - Complete - Waiting for Action, Employee status changed to as **Rest**.


- ### **Waiting For Action:**


  - If Employee moved to "**Ready to work**" then employee status changed to **Ready to work** category.

  - If Employee ***"Refuse to work"*** then Investigation process will start for the Employee and status changed to **Rufuse to Work** category.

  - If Employee request for Vacation, Then Leave Request will create for with Required Data if Employee eligible.

  - If Employee request for Retirment(Final Exit), then retirement request will create for Employee with required data.


    * In The Action fields are Following:

       ***1.Ready to Work*** - User move to process with Required stage.

       ***2.Refuse to Work*** - User move to process with **Refuse To Work** stage.

       ***3.Leave*** - User move to process with **Leave Request** stage.

       ***4.Final Exit*** - User move to process with **Retirement** stage.


<br>
<br>

### _**Refuse to Work**_

Transaction will creates with Sub-Category in different sources.

**Refuse to Work Process will start based on Return Reason (sub-category) as follows:**

   - **Request For Vacation:**

     - If Employee refuse to work and request for vacation after return, then Process starts with **Waiting For vacation** stage.

     - Then Employee status changed to **Waiting For vacation**.

   - **Request for Exit:**

     - If Employee refuse to work and request for Exit / Retirement after return, then Process starts with **Waiting For Exit** stage.

     - Then Employee status changed to **Waiting For Exit**.

   - Other Subcategory:

     - Process starts with **Under_Investigation** stage.

     - Employee status changed to **Under_Investigation**.


### ***Refuse to Work - Workflow:***

- ### **Under Investigation:**

   User can move to following required stage,

    * **Refuse to Work,**

       Moved to Waiting for Action and then Investigation process will start for Emloyee.

     * ***Ready to Work,***

       Moved to Required stages, and then employee status changed to Ready to work.

       * _In The Action fields are Following:_ 

          *  **1.Refuse to Work** - Moved to for Investigation Process.

          *  **2.Ready To Work** - Moved to Required stage.

- ### **Refuse to Work:**

  * Investigation process will start for Employee,

  * If Employee Refuse to Work and then Investigation process will start.

  * If Employee is Ready to work, then employee status changed to Ready to work.

  * If Employee is request for Vacation, then leave request will create with required data for Employee.

  * If Employee rquest for Final Exit, then Retirement request will create with required data for Employee.

     * _In The Action fields are Following:_

       * **1.Final Exit -** Moved to process Retirement request.

       * **2.Vacation -** Moved to process Leave Request.

       * **3.Refuse To Work -** start with Investigation.

       * **4.Ready To Work -** Moved to Required stages.


- ### **Legal Action:**



- ### **Waiting For Action:**

   Waiting for this satge to complete the process for Employee,

   **Leave** Request or **Retirment** Request for Employee.

   Once complete the Leave/Retirement Process for employee, and this stage complete with system integration.

- ### **Waiting For Exit:**

    Once Employee Exit completed then this stage complete with Employee Exit status.

<br>

### _**Dead**_

In Case of Employee is deceased, then Employee Status is Changed to **Dead**.


### ***Dead Workflow:***

- ### **Request:**

  - Required to register the Information about Employee Death into Portal, as Labour ID, Location and Date while Death.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** - Death reason or Any Information.

    * ***Location*** - Employee being which place to Locate while Death.

    * ***Date*** - Actual Date of Employee Death.


  - If Employee Worked with customer, Then Required to **end the contract** with Customer beacause of the Employee Deceased.

  - If Employee is on Lodging, then **Checkout** process will stat for Employee from the Lodging.
  

     * **_In The Action fields are Following:_**

        **1.Complete** - Complete and Moved to Action Stage..

- ### **Action:**

  - And then **Final settlement** will create in **Retirement** request, for Employee after Registered Dead in Portal .

  - Retirement will create, When Employee is deceased in Lodging and Working status.

  - In this stage, Request is move to **Complete** stage.

     * **_In The Action fields are Following:_**

       * **1.Complete** - Moved to Complete stage.

<br>

### _**Jail**_

 In This stage, The Employee status is Changed to **Absent**.

   - If employee is working with customer, Then Required to end the contract with Customer.

   - And If employee in lodging, Then checkout process will start for Employee from the lodging

### ***Jail Workflow:***

- ### **Request:**


  - Required to register the Information into Portal, about Employee while send to Jail, as Labour ID, Location and Date while Death.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** -  Reason or Additional Information.

    * ***Location*** - Employee Located place.

    * ***Date*** - Actual Jailing Date of Employee.

  - Required to move to Action Stage.

       * **_In The Action fields are Following:_**

          **1.Complete** - Moved to Action stage.


- ### **Action:**

    - If The Employee is **return** from Jail, Then Check-in process will start for the Employee. Once the **Checkin** is Completed for Employee then Moved to Completed stage.

    - If Employee Reqested for the **Vacation**, Then **Leave Request** process will start for Employee.

   - or The Employee terminated and moved to **Final Exit**, Then **Retirement** request will create for the **Final Settlement** to Employee.


      * **_In The Action fields are Following:_**

         **1.Vacation** - Complete and Move to Vacation Stage.

         **2.Final Exit** - Complete and Move to Final Exit/Retirement stage.

         **3.Return** - Complete and Return to Work.

<br>

### _**Hospital**_

In This stage, Employee status is changed to **Sick**.

And If Employee working with Customer, Then required to End the Contract with Customer.

### ***Hopital Workflow:***

- ### **New:**

  - Required to register the Information into Portal, about Employee while request for Hospital/Sick, as Labour ID, Location and while admitted to Hospital.

    * ***Labour ID*** - Employee Unique Identification Number

    * ***Remarks*** -  Reason or Additional Information.

    * ***Location*** - Employee Located place while request for Sick.


    And then User can move to following required stage,

     * **_In The Action fields are Following:_**

        **1.Sent to Hospital** - Complete and Moved to **Sent to Hospital** stage.

        **2.Sick Leave** - Complete and moved to **Sick Leave** stage.

        **3.Waiting for Action** - Complete and Moved to **Waiting For Action** stage.

- ### **Sent to Hospital:**

   In this stage, User can move to following required stage,

     * **_In The Action fields are Following:_**

       **1. Admitted to Hospital** - Complete and move to Admitted to Hospital stage.

       **2. Sick Leave** - Complete and move to Sick Leave stage.

- ### **Admitted to Hospital:**


  - When Admitted to Hospital stage is starts, then checkout process will start for Employee from lodging.

  - When Employee return from the Hospital, then checkin will start to lodging, and move to required stage.

    And then User can move to following required stage,

     * **_In The Action fields are Following:_**

       **1.Sick Leave** - Complete and moved to **Sick Leave** stage.

       **2.Waiting for Action** - Complete and moved to **Waiting for Action** stage.


- ### **Sick Leave:**

    If Employee request for Sick Leave, then Will start process for Sick Leave.

    And then User can move to following required stage,

   * **_In The Action fields are Following:_**

      **1.Waiting for Action** - Complete and moved to **Waiting for Action** stage

- ### **Waiting for Action:**

   In this stage, investigate the Employee after return to Lodging,

   And User can moves to required stages as follows.

   - ***Ready To Work,***

      Employee status will changed to _Ready to Work_, And moved to required stage.

   - ***Refuse To Work,***

      Employee status will changed to _Refuse to Work_, And moved to required stage.

   - ***Send To Hospital,***

     Employee status will changed to _Send To Hospital_, And moved to required stage.

     * And then User can move to following required stage,

         * **_In The Action fields are Following:_**

           **1.Ready to Work** - Complete and moved to Required stage

           **2.Refuse to Work** - Complete and moved to Refuse To Work stage.

           **3.Sent to Hospital** - Complete and moved to Send To Hospital stage.



