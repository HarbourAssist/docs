# Renewal Groups #

## Overview

In order for the Renewal engine to work correctly each boat requiring a recurring contract that will be part of a Batch Renewal Run needs to be Licensed to an Asset, have one or more Tariffs allocated to it and be assigned to a *Renewal Group*.  

?> For more documentation about Licensing click [here](Renewals/Licensing.md).

?> For more documentation about Allocating Tariffs click [here](Renewals/AllocatedTariffs.md).

When creating a Batch Renewal Run the *Renewal Group* is the criteria for selecting the correct group of accounts/boats to have orders raised against them.  

Renewal Groups can be set in any way you want depending on how you wish to group together your customers.  They could be set up by:-

- Site (for multi-site operators)
- Area
- Account type
- Order type
- Month etc. 

Renewal Groups are set by using a *Lookup* list and can be added to and amended at any time.

?> For more documentation about Lookups click [here](Administration/Lookups.md).

Each boat can only be in one boat *Renewal Group*.  

It is best to assign a boat to a *Renewal Group* at the point of setting up the account and boat details.

## Adding a Renewal Group to a Boat

To assign a *Renewal Group* to a boat, from the Dashboard screen select the boat by clicking on the boat name or using the *Boats* tab.

![image-20220121123505176](image-20220121123505176.png)

If you have used the Boats tab, select the boat by clicking on the boat name.

Select the *Renewal Group* by using the drop down options in either the *Set Renewal Group* or within the boat details itself.  

![image-20220121123921590](image-20220121123921590.png)

Alternatively, you can set the *Renewal Group* from the *Tariffs & Occupancy* screen at the same time as Licensing the boat and allocating the Tariffs. 

![image-20220121124215521](image-20220121124215521.png)