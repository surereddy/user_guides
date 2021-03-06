# Number Management

Acquiring and managing the phone numbers on an account is simple in Kazoo.  Using the available applications adminstrators can purchase new numbers with instant activation, manage features such the emergency address, assign to users or devices and move them between accounts.

> Who can use this feature?

> All adminstrators on any Kazoo deployment.

>> Keep in Mind: After clicking `Buy Numbers` you may be presented with the changes to the monthly billing amount.  Clicking `Accept` will allow the numbers to be purchased or `Cancel` will make no change.

## Purchasing the Company Main Numbers

1. Switch to the SmartPBX application and select the `Main Number` tab
![SmartPBX](smartpbx/main-number-local/step-1.png)

2. Expand the `Main Company Numbers`, then click the `Buy Numbers` and select `Local`
![SmartPBX main company numbers local](smartpbx/main-number-local/step-2.png)

3. Enter the area code for the desired location then click `Search`
![Local number area code search](smartpbx/main-number-local/step-3.png)

4. Select one or more numbers and click `Buy Numbers`
![Local numbers purchase](smartpbx/main-number-local/step-4.png)

5. The numbers selected will now be listed and will be active within 5 minutes
![SmartPBX main company numbers with local](smartpbx/main-number-local/step-5.png)

## Purchasing Company Toll-Free Numbers

1. Switch to the SmartPBX application and select the `Main Number` tab
![SmartPBX](smartpbx/main-numbers-toll/step-1.png)

2. Expand the `Main Company Numbers`, then click the `Buy Numbers` and select `Toll-free`
![SmartPBX main company numbers toll-free](smartpbx/main-number-toll/step-2.png)

3. Select a toll-free prefix then click `Search`
![Toll-free number prefix search](smartpbx/main-number-toll/step-3.png)

4. Select one or more numbers and click `Buy Numbers`
![Toll-free numbers purchase](smartpbx/main-number-toll/step-4.png)

5. The numbers selected will now be listed and will be active within 5 minutes
![SmartPBX main company numbers with toll-free](smartpbx/main-number-toll/step-5.png)

## Purchasing Numbers for Users

1. Switch to the SmartPBX application and select the `Users` tab
![SmartPBX](smartpbx/users/step-1.png)

2. In the column under `Phone Numbers` click on the row with the User to add a phone number to
![SmartPBX user phone number selection](smartpbx/users/step-2.png)

3. Select `Local` or `Toll-free` and follow the same steps as indicated above to complete the purchase.
![SmartPBX user phone number type selection](smartpbx/users/step-3.png)

## Purchasing Company Conference Numbers

1. Switch to the SmartPBX application and select the `Main Number` tab
![SmartPBX](smartpbx/main-conference/step-1.png)

2. Expand the `Main Conference Number`, then click the `Buy Numbers`
![SmartPBX conference number list](smartpbx/main-conference/step-2.png)

3. Select `Local` or `Toll-free` and follow the same steps as indicated above to complete the purchase
![SmartPBX conference phone number type selection](smartpbx/main-conference/step-3.png)

## Purchasing Company Fax Number

1. Switch to the SmartPBX application and select the `Main Number` tab
![SmartPBX](smartpbx/main-faxbox/step-1.png)

2. Expand the `Main Faxbox Number`, then click the `Buy Numbers`
![SmartPBX faxbox number list](smartpbx/main-faxbox/step-2.png)

3. Select `Local` or `Toll-free` and follow the same steps as indicated above to complete the purchase
![SmartPBX faxbox phone number type selection](smartpbx/main-faxbox/step-3.png)

## Setting the Company Emergency Address


1. Switch to the SmartPBX application and select the `Main Number` tab
![SmartPBX](smartpbx/main-number-features/step-1.png)

2. Expand the `Main Comany Numbers`, then click the gear icon next to the number and select `e911`
![SmartPBX company number list with features](smartpbx/main-number-features/step-2.png)

3. Enter the emergency address and click add
![SmartPBX emergency address entry](smartpbx/main-number-features/step-3.png)

4. Ensure the emergency enabled icon appears
![SmartPBX emergency address entry](smartpbx/main-number-features/step-4.png)

## Using Spare Numbers

>> Keep in Mind: A spare number is one that has been purchased for the account then `unassigned` but not deleted.

1. Switch to the SmartPBX application and proceed as you would for number purchasing
![SmartPBX](smartpbx/main-spare/step-1.png)

2. Click on `Add from Spare Numbers`
![SmartPBX company number list](smartpbx/main-spare/step-2.png)

3. Select the spare numbers and click on `Add selected numbers`
![SmartPBX company number spare](smartpbx/main-spare/step-3.png)

## Removing Numbers

>> Keep in Mind: A spare number is one that has been purchased then `unassigned`.

1. Switch to the SmartPBX application and and select the `Numbers` tab
![SmartPBX](smartpbx/numbers/step-1.png)

2. Click on `Spare Numbers` and select the numbers for removal
![SmartPBX number list](smartpbx/numbers/step-2.png)

3. Click the `Delete` option that appears
![SmartPBX number list with delete highlight](smartpbx/numbers/step-3.png)

4. If you are sure that the numbers are no longer required click `Delete number(s)`.  Once removed they are gone forever
![SmartPBX number delete accept pop-up](smartpbx/numbers/step-4.png)

## Listing all In-Use Numbers for the Account

>> Keep in Mind: An in-use number has an assignment to a company main number, user, device, SIP trunk, callflow, conference, pivot application, ect.

1. Switch to the Number Manager application
![Number Manager](number-manager/in-use/step-1.png)

2. Click on `In-Use`
![Number Manager in use](number-manager/in-use/step-2.png)

## Moving Numbers to Another Account

>> Keep in Mind: Only spare numbers can be moved between accouts, if a number is in use select the application using it and choose `unassign`

1. Switch to the Number Manager application
![Number Manager](number-manager/in-use/step-1.png)

2. Select the `Move To` option at the top of the list
![Number Manager in move to](number-manager/in-use/step-2.png)

3. Click on the account to move the numbers to
![Number Manager move to account selection](number-manager/in-use/step-3.png)
