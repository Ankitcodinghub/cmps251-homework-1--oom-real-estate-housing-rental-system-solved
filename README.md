# cmps251-homework-1--oom-real-estate-housing-rental-system-solved
**TO GET THIS SOLUTION VISIT:** [CMPS251 Homework 1- OOM Real Estate Housing Rental System Solved](https://www.ankitcodinghub.com/product/cmps251-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110101&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPS251 Homework 1- OOM Real Estate Housing Rental System Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
OOM Real Estate has different types of houses. They have one bedroom, two bedrooms, and three bedrooms apartments.

Renting Process:

Tenant details (see the class diagram) must be recorded. For resident tenants, the housing system needs to record additional details such as bank information and the tenant’s Qatari ID. For visitors, the passport number, visa entry, and expiry dates are recorded. Tenants must pay a deposit amount equal to 50% of house price they are renting, which will be refunded when they release from the housing in good condition. When the tenant releases the house any damages are evaluated and the cost of repairs is deducted from the deposit amount. The remaining deposit is returned to the tenant.

The following is a brief class diagram that describes classes in this system and their relationships.

Project Phase I requirements

1. Implement the entity classes for OOM Real State System as shown in Figure 1.

Inovice Explanation

+modifyIPayment(payment: Payment): void Update payment information.

+deletePayement(paymentId: int): String Delete a payment.

+addPayment(payment: Payment): void Add a new payment to the system.

+getPayment(paymentId: int): Payment Search for a specific tenant by their id

+calculateTotalPayment() : double Calculate total payment for the invoice.

2. Implement the OOM Real State class as described below.

OOM Real State System Explanation

+addTenant(tenant: Tenant): void Add a new tenant to the system (resident or visitor).

+findTenant(tenantId: int): Tenant Search for a specific tenant by their id.

+deleteTenant(tenantId: int): void Delete for a specific tenant by their id.

+addHouse(house: House): void Add a new House to the system (1 bedroom, 2 bedrooms or 3 bedrooms)

+findHouse(houseNo) Search for a specific house by its number.

+deleteHouse(houseNo) Delete for a specific house by its number.

+getHouseByAvailability(available: boolean) :

List&lt;House&gt; Get all available houses.

+releaseHouse(houseNo: int): invoice When a tenant leaves the house, the house status is updated to available.

The invoice of that house is returned

+findHouseRentalByTenantId(tenantId: int):

List&lt;HouseRental&gt; Returns all the houses rented by a specific tenant

+deleteHouseRental(tenantId : int): void Deletes specific houseRental by specific tenantId.

+saveData(): void Save data to file

+loadData(): void Load data from file

3. Add an App class having the main method to test all the methods of the application. In phase I, any data needed should be hardcoded. The app should display the results to the console. There is no need to ask the user to enter any data during phase I.

Project Phase II requirements

Your system should have a GUI interface to interact with system users and should use files to save data permanently. (This requirement is to be finished in Phase II)

Below are some of the screenshots for the GUI you suppose to create in phase II of the project. The following screenshot are guidelines of how the system should look like. And they are the minimal requirements. However, if some of you would like to improve the design or implement more functionalities, then you are free to do so.

Main UI Window

This window is loaded when you first start the application.

Figure 1

Main House Window

This window is shown when the user clicks on the House Button in the MainView [Fig.1].

Figure 2

Add House Window

This window is shown when the user clicks on the Add Button inside the House View shown [Fig.2]

Figure 3

Update House Window

This window is shown when the user clicks on the Update Button inside the House View shown [Fig.2]. You will be required to populate the selected house info into a form to allow the user to edit.

Figure 4

Main Tenant Window

This window is shown when the user clicks on the Tenant Button inside the Main View shown [Fig.1]

Figure 5

Add Tenant Window

This window is show when the user clicks on the Add Button inside the Tenant View shown [Fig.5]

Figure 6

Update Tenant Window

This window is shown when the user clicks on the Update Button inside the Tenant View shown [Fig.5]. It is similar to the Update House.

Figure 7

Rentals View

This window is shown when the user clicks on the Rental Button inside the Main View shown [Fig.1].

The following are the steps you need to implement.

1. You should populate the tenant id and house numbers in the two drops down elements [Tenant, House].

2. When the user selects a tenant id, house no, rent start and end dates, and presses on Rent. Then you need to use this information to create a rental object.

Hint: before creating the rental object, use the findHouse and findTenant methods you created in phase 1, to get all the house and tenant objects .

3. Create a Rental Object using that information.

4. Display the properties of the rental object, as shown below.

Hint: the color code for the top part is “#6ec2de”. You are free to use any color.

Instructions for Phase 2:

1. All the instruction in phase I apply here too, as this is instructions are just a continuation of the previous phase.

4. Each group should submit one softcopy of their work by uploading an archive of their project folder to the course website on Blackboard under your group and also update their Phase I report by adding the phase II GUI.

5. Each member MUST submit a one-page confidential report (called the self-report) describing his/her exact contribution to the project and explaining the advantages and disadvantages of working in teams, based on your current experience with this project.

Evaluation criteria:

The breakdown of the project grade is as follows:

• 30% for the functionalities required above, and the report that shows the code and the results of all the test cases. This includes correct indentation and formatting of your code, use of a meaningful variable name, abiding by Java naming conventions etc. (Phase I and II)

• 20% for authoring and producing the Javadoc documentation (Phase I)

• 25% for adding a GUI to the application. (Phase II)

• 15% File management (saving, loading, updating) (Phase II) • 10% for the presentation of the work (Phase II)

• The program does not compile (-100%)

• If you are not attend the discussion (-100)
