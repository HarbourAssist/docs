# Batch Runs #

Once your *Batch Types* are set up the next stage is to create the *Batch Renewal Run*.

## **Batch Renewal Video**

<a href="https://vimeo.com/782895611" target="_blank"> <img src="https://i.vimeocdn.com/filter/overlay?src0=https%3A%2F%2Fi.vimeocdn.com%2Fvideo%2F1571853880-67bca60f4f030b017c7100e859ab65cc27798d0e26b900d65fa3bcbda3baaf9e-d_295x166&src1=http%3A%2F%2Ff.vimeocdn.com%2Fp%2Fimages%2Fcrawler_play.png" /> </a>

From the *Home* screen go to *Batch Tools*.

![image-20220224125725461](image-20220224125725461.png)

From the drop down list, select *Batch Runs*.

![image-20220224125856907](image-20220224125856907.png)

Click on *Create Batch*.

![image-20220224130007853](image-20220224130007853.png)

This will bring up a full list of all the *Batch Types* that have been created.  Select the one you wish to use.

![image-20220224130124450](image-20220224130124450.png)

The *Batch Run* screen shows you which *Batch Type* you have selected.

Now select the Site to include (multi-site operators have the options to select one or multiple sites) and the Pricebook to use.  

?> More documentation [here](AccountsOrdersPayments/TariffsPricebooks.md).

![image-20220224130830456](image-20220224130830456.png)

Now complete the rest of the information required.  Some information will be populated automatically from the *Batch Type* that you have selected, however you can edit this if necessary.

- **Order created date** - this is the date that will show on the draft order.  It will default to todays date, so unless you want to change this, just leave it blank.
- **Occupancy to create** - this will auto populate from the Batch Type, so unless you wish to amend this, just leave it as it is.  This can be left blank if you do not with to create an occupancy (membership renewals for example).
- **Start Date** - this is the start of the contract and any associated occupancy.  Use the calendar pickers to set a date.
- **Departure Date** - this is the end of the contract and any associated occupancy.  Use the calendar pickers to set a date.
- **Include Uninvoiced Meter Readings** - this will auto populate from the Batch Type.  If you wish to include meter readings this box should be ticked.
- **Renewal Groups** - this will auto populate from the Batch Type, but you can add or amend the groups to be included at this stage.

Once all the information has been populated, click on *Calculate Entries*.  

![image-20220224131154223](image-20220224131154223.png)

This will create a list of all customers who meet the Tariff and Renewal Group criteria that have been set.

![image-20220224131334149](image-20220224131334149.png)

If you are happy that the right customers have been selected, click on *Generate Orders*.  This will create *Proposed* orders for these customers.  Proposed orders do not create a balance on the customer account or show on their portal and are fully editable.

![image-20220224131517468](image-20220224131517468.png)

Once the *Proposed* orders are created you will see a summary of the Financial values of the orders and also details communication preferences of the customers.

![image-20220224132015815](image-20220224132015815.png)

You can check the Orders by clicking on the Order ID number which will take you straight into the generated order.

![image-20220224132111823](image-20220224132111823.png)

![image-20220224132202750](image-20220224132202750.png)

At this stage you can add, amend and remove any tariffs as necessary - for instance, you may have 1 customer where you have agreed a reduce rate - this is the point to make this adjustment.

You can also delete the order if it isn't required - this way you don't have to re-run the whole Batch Run - if an order is deleted the account will still show in the Batch Run, but the Status will show *Invalidated*. 

?> NB.  To be able to delete any orders the User will require the Permission of **OrderCanDelete**.

![image-20220224132441848](image-20220224132441848.png)

If you want to view what the paperwork you will be sending out to customer looks like you can view this by clicking on the green *Actions* button on any of the entries and selecting View Document.

![image-20220224132830371](image-20220224132830371.png)



At this stage there will be a *Preview* watermark on the document.

![image-20220224133213876](image-20220224133213876.png)

You can also send a sample of the email that will be sent to those who have opted to receive their communications by email.  Insert your email address in the *Email Testing* cell and click on *Send Samples*.

![image-20220224133624170](image-20220224133624170.png)

When you are happy that everything is correct, the next step is to convert the Orders.  

![image-20220224133711734](image-20220224133711734.png)

The screen updates to show you that you are now at the *Orders Converted* stage. The Orders have now moved from *Proposed* to *Draft* and will show as such on the customer account page and on the customers portal.  They are still fully editable at this stage though.

![image-20220224133833458](image-20220224133833458.png)

?> NB.  As renewal orders are normally created well in advance of the renewal date, they are sent to the customers as a Draft order, this enables the customer to come back to you with any necessary changes and you will be able to make these changes to the Draft order rather than having to raise a credit note and a new order.

Now you can start to dispatch the Orders to your customers.  Click on *Dispatch Emails*.

![image-20220224134139640](image-20220224134139640.png)

You will be asked to confirm you wish to continue - click OK if you are happy.

![image-20200113170106094](image-20200113170106094.png)

To print the Orders for those customers who wish to receive them by post, click on the *Download* button and select either Word or PDF.

![image-20220224134434936](image-20220224134434936.png)

If there are a large number to print and you wish to break it down into smaller groups, you can select the number of pages to output - once you have done this click *Generate*.

![image-20220224134526980](image-20220224134526980.png)

You will note that the Preview watermark has now been removed, so you can print in the same way you would any other document.

The Statistics now show that the emails have been sent and this also shows against the line entry.

As the Orders are paid, they will be Confirmed and given a Tax Point Date of the date of the payment.  The Finance statistics will update automatically.

![image-20200113172406236](image-20200113172406236.png)

On viewing the Orders tab of the customers account you can see by the icon which Orders have been created by a Batch Run.

![image-20220224135722433](image-20220224135722433.png)

