## SD Intelli Pricing Releases

### 3.4.1

#### Enhancements

- AppSource App - The Price Includes VAT option was removed from the Price Group Card. The Price Includes VAT on the Customer Card is used to determine if VAT is included in the price on the Price Group.

#### Bug Fixes

- AppSource App - An issue was fixed where the Sales Line Discounts were applied if Allow Line Disc. was set to No on the Price Group Card.

- AppSource App - An issue was fixed where the Sales Invoice Discounts were applied even if Allow Invoice  Disc. was set to No on the Price Group Card.

### 3.4.0

#### Enhancements

- AppSource App - Unit Price precision on the Price Group Lines has been extended to support up to five decimal places across Standard, Contract, and Listed pricing levels.

- AppSource App - An event has been added to the OnUpdateUnitPriceByFieldOnAfterFindPrice function within the SDY IP Multi-Group Pricing codeunit. This allows the standard SD Intelli Pricing logic to be bypassed, enabling the application of custom pricing logic when needed.

- AppSource App - Tooltips on the Price Group Worksheet were updated.

- AppSource App - The Price Book report has been retired. Users should now use the Price Checker report as its replacement. The Price Checker report supports printing, exporting to Excel, and emailing directly to users, offering enhanced flexibility and functionality.

- AppSource App - Layout changes were made to the Price Checker report.

- AppSource App - The notification prompting users to activate a free trial of SD Intelli Pricing on a fresh install has been limited to display no more than once per hour on standard role centres.

#### Bug Fixes

- AppSource App - Resolved an issue where the Price Checker could hang when printing the price checker report or filtering on the Price Checker Lines.

- AppSource App - Corrected an issue where promotions were not applied to sales lines if the Ending Date was set on the Price Group header and the Order Date was earlier than the current date. Promotions now apply correctly under these conditions.

### 3.3.2

#### Enhancements

- AppSource App - The licence check in the Sales Invoice Copy Doc functionality was reworked.

- AppSource App - A link to the user guide on the DynamicsShop page was added to the About page and to the Manage Subscriptions page.

- AppSource App - A minor change was made to the Product Activation page.

### 3.3.1

#### Enhancements

- AppSource App - A modification was made to the Setup Wizard.

- AppSource App - A minor enhancement was made to the user experience flow on initial install of SD Document Sender.

### 3.3.0

#### Enhancements

- AppSource App - DRS values were surfaced on the Sales Credit Memo.

- AppSource App - Actions were surfaced to manually link and clear the link between DRS lines and item lines on the Posted Sales Invoice Subform and the Posted Sales Credit Memo Subform. This is to allow you to link DRS lines that have not come from SD Intelli Pricing to your Invoices and Credit Memos.

- AppSource App - A new Licence Install and Setup Wizard was created.

- AppSource App - The notification to activate the app, displayed on fresh install of SD Intelli Pricing, was added to the standard Business Central role centres.

- AppSource App - Changes were made to the Manage Subscriptions page.

- AppSource App - The Lead Subscription Link from the Request Subscription action in the Product Activation page was updated.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps.

- AppSource App - A minor change was made to the About page.

### 3.2.4

#### Enhancements

- AppSource App - Changes were made to remove promotions and levies functionality from Blanket Sales Orders. Sales Credit Memos and Sales Return Orders no longer process promotions. Copy Document functionality does not copy levy lines into a Credit Memo as the levy lines are recalculated when the document is released or posted.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps. 

#### Bug Fixes

- AppSource App - A fix was made to an error that was raised when the same item/customer/unit of measure combination has multiple price groups.

### 3.2.3

#### Enhancements

- AppSource App - The D365 BUS FULL ACCESS permission set was extended to include the SD Intelli Pricing objects.

### 3.2.2

#### Enhancements

- AppSource App - A change was made to the Levies and Promotions codeunits to handle automatic sales order approval workflows.
  
### 3.2.1

#### Enhancements

- AppSource App - The logic behind the Select Prices action on the Worksheet was reworked.

- AppSource App - The functionality behind insertion of lines to promotions and levies price groups was reworked. 

- AppSource App - Update to comments on the lines in the Levy Price Groups. 

#### Bug Fixes

- AppSource App - The link on Promotions and Levies in Price Group FactBox was fixed.

- AppSource App - A fix was made to apply levies to the free promoted items inserted on the lines.

### 3.2.0

#### Enhancements

- AppSource App - Functionality was added to allow for insertion onto sales lines of more than one levy for the same item. 

- AppSource App - Add the Levy and Promotions Tables to the SD Intelli Pricing permission sets.

- AppSource App - A change was made to the licence expiry notification. The logic for checking for expiry dates was reworked.

- AppSource App - Enhancements were made to the App Request Subscription page.

- AppSource App - ToolTips were updated in the About, Product Activation, and Tenant Subscription pages.

- AppSource App - Additional phrases were added as search phrases for the SD Intelli Pricing pages.

### 3.1.1

#### Enhancements

- AppSource App - Changes were made to the levy quantity calculation to handle items with a base UoM that is higher than the single logical unit that is setup to pay the DRS.

- AppSource App - The SDY IP Price Group Lines page is now editable.

- AppSource App - The Edit in Excel With Filters functionality is deprecated in BC25. The SDY IP Price Line Worksheet was updated to use the Edit in Excel And Edit in Excel Filters Codeunits.

### 3.1.0

#### Enhancements

- AppSource App - A change was made to the Levies and Promotions CodeUnits to handle sales order approval workflows.

### 3.0.0

#### Enhancements

- AppSource App - A new Promotion Level with associated functionality was added to the Price Group Card. This new Level allows users to setup BOGOF and BANDED promotions which are auto inserted into a sales line.

- AppSource App - A new Levies Level with associated functionality was added to the Price Group Card. This new Level allows users to setup various levies which are auto inserted into a sales line. This functionality can be used for levies such as Sugar Tax and DRS levies.

- AppSource App - Improvements were made to the Unused Pricing Calculations logic.

- AppSource App - Improvements were made to the Margin Alerts Calculations logic.

- AppSourcce App -The SD Intelli Pricing fields on the Sales Lines were mirrored to the Sales Archives.

- AppSource App - Various UI changes were made to the Price Group Card.

- AppSource App - KPIs for Prices Unused, Prices Expiring and Margin Alerts were surfaced on the Setup Card.

- AppSource App - UI changes were made to the Role Centre. Duplicate Cues were removed.

- AppSource App - A new SD Intelli Pricing FactBox was added to the Item List and Item Card.

- AppSource App - A new SD Intelli Pricing FactBox was added to the Customer List and Customer Card.

- AppSource App - The SD Intelli Pricing Item FactBox was surfaced on the Sales Quotes, Sales Orders, Sales Invoices and Sales Credit Memos so users can easily see if there is a promotion associated with the item on the Sales Line.

- AppSource App - An Item Category Margins KPI was surfaced on the Setup Card.

- AppSource App - Tooltips and Captions in SD Intelli Pricing were updated.

- AppSource App - Changes were made to Enum options so the DemoData file and the Assisted Setup functionality were updated.

### 2.1.8

#### Enhancements

- AppSource App - An enhancement was made to the revalidation logic of Sales Line Prices if Order Date, Document Date, Requested Delivery Date or Shipment Date are changed on the Sales Header.

### 2.1.7

#### Enhancements

- AppSource App - A prompt was added to allow users to choose whether to re-validate the pricing on the Sales Lines if Order Date, Document Date, Requested Delivery Date or Shipment Date is changed on the Sales Document Header.

- AppSource App - The logo in App was updated to the new logo.

- AppSource App - The Links in the About Page were updated.

### 2.1.6

#### Enhancements

- AppSource App - A new event OnBeforeOnAfterValidateShipmentDateOnSalesLine was published.

- AppSource App - The links in the About page were updated.

### 2.1.5

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Intelli Pricing to fix an issue that would raise an error when the language is changed from English to another language.

- AppSource App - The SD Intelli Pricing Tenant Subscriptions page had an incorrect caption. This was fixed.

- AppSource App - An error was raised in the Assisted Setup import if non sequential enum values exist in the imported data. This was fixed.

- AppSource App - When selecting SD Intelli Pricing activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

### 2.1.4

#### Enhancements

- BCv21 App - The Licence Message displayed on first install of SD Intelli Pricing was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data.

### 2.1.3

#### Enhancements

- BCv21 App - A change was made to allow users to edit the Price Group Lines on the Worksheet and in a new page Edit Price Group Lines using the Edit in Excel functionality.

- BCv21 App - The caption of the new Price Group Lines page was updated to SD Intelli Pricing Edit Price Group Lines.

- BCv21 App - On the Role Centre page two separate queues with actions were merged into a single queue to keep the actions grouped together.

### 2.1.2

#### Enhancements

- BCv20 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant. 

- BCv20 App - The Licence Expiry message/notification was updated to display the App Name as part of the message. 

- BCv20 App - The Product Activation Page was updated to point to the new CRM URL. 

- BCv20 App - The ToolTips were updated to look at our new website. 

- BCv20 App - The links in the About Page were updated to point to new urls. 

- BCv20 App - Permissions were changed from XML to use AL permission extensions. 

#### Bug Fixes

- BCv20 App - Fix to issue with adding the same item more than once to a price group that is valid for the same time frame. 

- BCv20 App - A fix was made to the code for licence key checks on the SD Intelli Price Role Centre. 

### 2.1.1

#### Enhancements

- BCv19 App - Added the Latest Version of the product and the AppSource URL to the About Page. 

- BCv19 App - Added the Latest ISV Licence Control with fix to Free Trials in Public Environments. 

#### Bug Fixes

- BCv19 App - Fixed an issue where after getting a message that the Free Trials were exceeded and clicking on the Assisted Setup action an error was raised.

### 2.1.0

#### Enhancements

- BCv18 App - The latest ISV Controller was added to the product.

- BCv18 App - A change to auto populate start and end dates on the price lines based on the header start and end date was removed.

- BCv18 App - Multi group prices should be excluded from Sales Lines if the dates on the Price Group Lines are not within the Price Group Header date ranges.

- BCv18 App - The latest licence controller changes were added to the product.

- BCv18 App - The names of the FactBoxes were updated to Price on Sales Lines and Price on Posted Sales Invoices to reflect the flowfield.

- BCv18 App - The FactBoxes were changed to remove the check on the posting dates as the posting date will vary depending on the take effect date and not on the dates on the price group line.

- BCv18 App - The Price Checker was changed to use the Date entered to filter down on price group lines and not filter on the header.

- BCv18 App - A new SD Intelli Pricing Price Checker Report was created. Visual changes were made to the Price Checker Report - column headings were changed and aligned; the name of the report was updated.

- BCv18 App - Visual changes were made to the SD Intelli Pricing Expiring Prices Report - column headings were changed and aligned; the name of the report was updated.

- BCv18 App - The caption on the Type column on the Price Group Link page was updated to Level as per the Price Group Card.

- BCv18 App - Updating the Ending Date on a Price Group Header should only update the Ending Date on the Price Lines during an initial on insert of the line and not update pre-exiting lines.

- BCv18 App - The code was reviewed to ensure that the Multi Group pricing functionality in SD Intelli Pricing works with the new Microsoft Dynamics 365 Business Central sales pricing experience.

- BCv18 App - A typo was fixed on the message displayed on import of Assisted Setup.

- BCv18 App - The ISV Licence Controller prompt is now displaying when the Setup Card is opened and the licence has not been activated.

- BCv18 App - The HTTPClient Request option in the Extension Management page is switched on automatically on install of the product.

- BCv18 App - The Price Checker searched up until the first price group was found for a Customer and did not search for further Price Groups. The Price Checker now searches for more than Price Group per Customer.

- BCv18 App - Displayed the Take Effect Date on the Customer Price Group Link.

- BCv18 App - The check that a Price Group Card must be disabled when updating Price Lines was removed.

- BCv18 App - The logic was changed in the Licence Controller not to allow more than one trial licence of the product in an organisation. 

- BCv18 App - A count of the distinct items on the Price Group was added to the Price Group Details factbox.

- BCv18 App - Reviewed code to ensure that users receive a message on a Sales Quote that the licence has expired even if the Pricing Method is set to Standard.

- BCv18 App - When creating price group lines the start and end date from the price group header are now auto-populated on the lines for ease of user input.

- BCv18 App - On the Prices Unused Card users can select a date rather than input the number of days for the Ignore Prices newer than field.

- BCv18 App - The Prices unused..X days on the Prices Unused Card was recaptioned to Prices unused in X days. 

- BCv18 App - The Take Effect Date on the Price Checker Card was updated to Date.

- BCv18 App - The permission sets for SD Intelli Pricing were updated.

- BCv18 App - The Price Worksheet was recaptioned to Price Group Worksheet.

- BCv18 App - The Refresh Profitability Alerts cue in the Role Centre was recaptioned to Refresh Margin Alerts.

- BCv18 App - Changes were made to the SD Intelli Pricing Price Checker Report - the report caption was changed and the layout was changed to landscape.

- BCv18 App - Changes were made to the Price Checker Card for greater ease of use. Also the option to email the report was missing from the card.

- BCv18 App - Changes were made to the Prices Expiring Card for greater ease of use.

- BCv18 App - Changes were made to the Prices Unused Card for greater ease of use.

- BCv18 App - Searching on Price Group Link in the Tell Me returned two pages - this was updated to return only one page on searching for Price Group Link.

- BCv18 App - Functionality was added to allow users to bulk add and link Customers to a Price Group.

- BCv18 App - The caption of the Max Group Date Range in Days field on the Price Group Card was changed to Max Date Range in Days. 

- BCv18 App - A typo was fixed in the Prices Unused Card.

- BCv18 App - A change was made to prevent users from making changes to the price on a Sales Line if the line has come from a Listed Price Group.

- BCv18 App - The Item Unit Price was moved to the left of the Unit Price on the Price Group Lines to allow for easier entry and comparison.

- BCv18 App - A Price Group Details FactBox was added to the Price Group List page.

- BCv18 App - Minor visuals were made to the Setup Card - fields were moved to FastTabs, fields were recaptioned, fields were reordered, FastTabs were recaptioned.

- BCv18 App - Not enabling the Allow Open Ended Date flag on the Setup Card should force users to enter Price Group End Dates on the Price Group Header.

- BCv18 App - A changes was made to enable the HTTPClient Request on install of the product.

- BCv18 App - Changes were made to the Licence Controller functionality. 

- BCv18 App - A new report was created to print off in the Price Checker card. The report prints a price book at a date, print for today or for a future date. The report finds the lowest price and filters on Customer, Take Effect, and Category.

- BCv18 App - Changes were made to the column order of the Price Group Lines.

- BCv18 App - Various changes were made to the SD Intelli Pricing Setup Card including creating new FastTabs and regrouping fields. 

- BCv18 App - Changes were made to the Price Group Card including adding checks when a Price Group is enabled.

- BCv18 App - A change was made to default the Max Group Date Range and Take Effect Date on the Setup into the Price Group card.

- BCv18 App - The Price Group Report was changed to group by Item Category and can be run at Take Effect Date.

- BCv18 App - Changes were made to the Price Line History FactBox and captions on the FactBox were updated.

- BCv18 App - A change was made to an action caption in the SD Intelli Pricing Price Worksheet.

- BCv18 App - Visual changes were made to the SD Intelli Pricing Price Worksheet - columns were added and re-ordered.

- BCv18 App - The Filters captions on the Select Prices request page were updated with correct captioning.

- BCv18 App - A cue to the Price Worksheet was added to the SD Intelli Pricing Role Centre.

- BCv18 App - The Default Threshold Margin % field was surfaced on the Margin Alerts Card.

- BCv18 App - Changes were made to the Price Group card - FactBoxes were reordered and a new FactBox for Price Group Lines was created.

- BCv18 App - The Variant Code on the Price Group Lines was resurfaced on the Price Group lines page. 

- BCv18 App - A KPIs FastTab was added to the SD Intelli Pricing Setup Card.

- BCv18 App - Standardised the naming of Price Books to Price Groups.

- BCv18 App - The prompt for the inactive licensing on the SD Intelli Pricing Role Centre was removed.

- BCv18 App - The SD Intelli Pricing Price Group Setup page caption was updated to SD Intelli Pricing Setup.

- BCv18 App - The option to Update the Price Book on Item Update was removed from the Price Group card.

- BCv18 App - Functionality was added to update the unit price when a shipment date is changed on the sales line level and not just the sales header level.

- BCv18 App - Fixed an issue with a lookup field on the SD Intelli Pricing Customer Take Effect Settings page.

- BCv18 App - When choosing the Product Activation action a message is now displayed prompting the user that they need to ensure they have enabled HttpClient Requests in Extension Settings.

- BCv18 App - The code was checked to ensure that licence expiry prompts did not affect the product's functionality. 

- BCv18 App - A test package was created for the SD Intelli Pricing App.

- BCv18 App - Translation files were created as part of the technical validation for AppSource submission.

- BCv18 App - Permission sets were created for SD Intelli Pricing.

- BCv18 App - The SD Intelli Pricing Price List Report was changed based on the standard report Item Price List (ID 7050).

- BCv18 App - Assisted Setup was added to the product.

- BCv18 App - Name and description fields were increased to 100 characters in length as per the standard D365BC change.

- BCv18 App - Our ISV Licence Controller was added to the product.

- BCv18 App - Various changes were made to the code base for submission to AppSource. 

- BCV18 App - The code base was converted from D365BCv14 to D365BCv18.

- BCv18 App - Detailed Price Line KPIs were added to a FactBox surfaced on the Price Group page.

- BCv18 App - The SD Intelli Pricing code base was updated as standard Codeunit Sales Price Calc. Mgt was marked for removal.

#### Bug Fixes

- BCv18 App - Fixed an issue where the Price Checker functionality was disregarding the end date filter when "Allow Open Ended Groups" was enabled on the SD Intelli Pricing Setup card.

- BCv18 App - When selecting prices into a Worksheet a blank line was always inserted. Code was added to remove the insertion of the blank line.

- BCv18 App - A fix was made to an AL error raised on input of items on the Price Group Worksheet.

- BCv18 App - Overwriting an Item No. on a Price Group Line did not instantly update the Item Unit Price from the Item Card.

- BCv18 App - A Listed Price Group Line was set up for an Item and Customer but an error was raised when trying to add the item to the Sales Line.

- BCv18 App - A fix was made to an issue where running the SD Intelli Price List report was causing the system to crash out.

- BCv18 App - Fixed an issue where the Prices Expiring cue/card was not picking up lines that were expiring.

- BCv18 App - A fix was made to solve an issue where when adding a Price Group Line to a Price Group the line was filtered out of the Price Group.

- BCv18 App - The Price Group Code in the Price Group Link was missing yet the FactBox was still showing the link.

- BCv18 App - Fixed an issue where adding a record in the P rice Group Link was not always saving the record.

- BCv18 App - A fix was made to an issue where users were unable to link a Customer to a Price Group in the Price Group Card using the Add Customers to Group action. 

- BCv18 App - The Product Activation page was changed to disable the Activate button unless a Product Key is filled in to avoid an error being raised when Activate is chosen.

- BCv18 App - A fix was made to default the price to the Item Unit Price when no price is found if the option is selected in the SD Intelli Pricing Setup card.

### 2.0.1

#### Enhancements

- BCv14 App - The Licensing Controller was added to the product.

- BCv14 App - The functionality in the Price Group Setup related to the Default to Item Unit Price was reworked.

### 2.0.0

#### Enhancements

- Updated details in the About Action and surfaced on the Setup Card.

- Removed the standard NAV OneNote, Notes and Links Actions from the SD LTA pages.

- Take effect price is based on order date, shipment date or delivery date.

- Added KPIs for the price lines: count of times price used; count of customers used; last date price used.

- Created an Activity Panel for Sales Pricing.

- Updated the List Price functionality to restrict items on sales orders if a listed price book exists.

- Made a change to present soon to expire prices as KPIs.

- Renamed the product from SD Multi Group Pricing to SD Intelli Price.

- Visual changes were made to the Price Group Setup.

- Created price checker functionality.

- Created an Activity Panel for the price books.

- Added price book price change control (% increase % Decrease) to the Price Worksheet.

- Changes were made to the Price Group Header.

- Added our standard About Action and surface on the Role Centre and the Setup Card.

- Created a Role Centre.

- Updated the Usage Category property on pages and reports.

- Removed standard NAV One Notes and Links on pages.

- Restamped the product version as per ISV guidelines.

- Renamed the objects as per ISV guidelines.

- Created a new Price Book report.

- Converted the v2.0.0 2018 code base to D365BC AL extensions.

### 1.0.1

#### Enhancements

- Split Multi-Group Pricing into it own project

- For all ISV Role Centres - split the Activities out into individual pages.

- Renamed namespace to Simply Dynamics.

### 1.0.0

#### Enhancements

LTA module: 
- Upgraded, renamed and renumbered code for LTA module. 
- Initial Code Merge. 
- Created Readme.txt. 
- Reordered pages. 
- Code restructure. 
- Created Event Hooks for LTA module. 
- Created and LTA Setup Card and table. 
- Created Charts for the LTA module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center.
- Generated Help files. 
- Add an option to open Sales Invoices and Credit Memos from the LTA Ledger Entry Lines on the LTA Ledger Entry Card. 
- UI improvements to the LTA Book Card. 
- Reordered fields in the General FastTab of the LTA Book Card for ease of user input. 
- Display the Item No. and the Item Description fields by default in the SD-FB LTA Price Group Line Page. 

MGP module: 
- Upgraded, renamed and renumbered code for MGP module. 
- Initial Code Merge. 
- Created Readme.txt. 
- Reordered pages. 
- Code restructure. 
- Renamed the List option to Standard to reflect functionality. 
- Created Charts for the MGP module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center. 
- Generated Help files. 
- Added a new flowField on the MGP Price Group table to count the number of records on the Price Group Line. 
- Group the Price List report by Item Category Code 
- In the Price Group Line Page - ensure the start and end dates are within the price book header start and end dates. 
- In the Price Group Line Page, to facilitate ease of data entry, on insert of a new line, default the UOM to the Item Sales UOM. 
- In the Price Group List, show the number of price lines associated with the Price Book. Allow KPI drill down to the Price Line Page. 
- In the Price Line Worksheet, change the Action Caption from Select prices to Get Prices. 
- Price Line Worksheet to allow the user to filter and make price changes easier, flow fields to the Item Category and Product Group were added to the table to allow users to filter and select for easier price changes. 

Catch Weight and Expiry Dates module: 
- Created new tables, pages and associated functionality for Item Extended FANDB, Item Units, Item Shelf Life, Item Shelf Life Worksheet, Item Units Worksheet Created Readme.txt. 
- Reordered pages. 
- Keep extended item table in sync with item table using events. 
- Created a chart for the Catch Weight and Expiry Dates module and display in the Role Centre. 
- Created XMLports for Import/Export of Setup and Data. 
- Created a Role Center. 
- Generated Help files. 
- Created and Item List Page. 
- Created Extended Item Card Part Page. 
- Fixed the vertical alignment of the fields in the SD-FB Item Card. 
- In the Item Card SD-FB Item Card fixed the width of the SD FB fields in the Catch Weight Fast tab (the Avg and Min Weight fields). 
- In the SD-FB Item Shelf Life List page, displayed the Item description of the Item in Item No. 
- In the Stock Units Worksheet, displayed the Item Description for the Item No. 
- In the SD-FB Item List, moved the Catch Weight Enforcement and Shelf Life Enforcement columns beside the Item Description column.

#### Bug Fixes

LTA module: 
- Fixed bug whereby filters were not applying correctly if two LTA Books exist for the same Customer. 
- Settlement Amount and Total Settlement Amounts are calculating incorrectly. 
- In the LTA Book Page, in the Accrual/Settlement Fast Tab, the Field Captions are not displaying in full. 
- Fix the LTA Setup - No. Series to act as per standard NAV number series. 
- Calculation issue with LTA - refactored the code and restructured it to improve the functionality and to make it easier to understand from an end users point of view. 
- G/L Account not being stamped in the LTA Ledger Card - when the LTA Worksheet generates Accruals or Settlements, the G/L account on the LTA Book is not being stamped on the LTA Ledger Entry. 
- Error thrown when selecting the Accrual/Settlement Report Action from the LTA Worksheet. 
- Start and end dates on the Price Group Line should be within Price Group Header start and end dates. 
- Display the Item No. and Item Description by default in the SD-FB LTA Price Group Line Page, currently users would have to select choose columns to display the Item No. and Item Description. 
- LTA - Accrual Calculation - A Credit Memo quantity is treated as an Invoice quantity in the Accrual and Settlement Calculations. The amount for Credit Memo is being calculated as a positive amount rather than as a negative amount. 

Catch Weight and Expiry Dates module: 
- Fix spelling mistake in the SD-FB Item Card.
- In the Freeze Down Journal and the Reclass Journal fields in the SD-FB Item Extended Card and the SD-FB Item Card incorrect Journal Templates are displaying on drilldown. The Freeze Down Journal displays a list of Journals with a Journal Template Name of "RECLASS". While the Reclass Journal displays a list of Journals with a Journal Template Name of "Phys. Inv". 
- In the SD-FB Item Shelf Life List Page, fields are not being re-set/updated on change of Cross-Reference Type. 
- Drilling down on the Customer Min Shelf Life rules and the Vendor Min Shelf Life Rules from these pages is showing records for all Item Nos and not the Item that the user is currently on. 
- In the SD-FB Item Card selecting the Catch Weights and Shelf Life Action raises an error.
- Users should not be able to insert records into the Item Units Page. This page should be read only. 
- The following fields were moved from the Item Extended table to a Setup table - Freeze Down Journal Template, Freeze Down Journal Batch, Campaign Location Code, Campaign Reclass Journal Temp., Campaign Reclass Journal Batch. 
- SD-FB Item Shelf Life WrkSheet - do not allow manual record input into this page. The only field users can update is the Confirm Action Checkbox. 
- A rename record message is raised on input of record into the SD-FB Item Shelf Life List Page. 
- The Description field on the Item-Cross References Page should be non-editable. 
- The Description field on the Item Shelf Life Worksheet should be non-editable. 
- In the Role Centre in the Catch Weights and Shelf Life Activity Group, the Cue link was renamed to Item Shelf Life to match the Navigation Pane. 
- Removed the New Item Unit link in the Role Centre from the Catch Weights and Shelf Life Activity Group as users cannot manually create an Item Unit Ledger. 
- Unit Stock Worksheet - when entries are calculated, records that have no stock location are not brought into the worksheet.
- The Item Units Stock Worksheet should calculate the current unit item count up to the specified posting date (..Posting Date). 
- In the Goods In Shelf Life functionality, when receiving a PO the Expiration Date, calculated off the Default Purchase Shelf Life for the Item, is raising an error as the Expiration Date calculation (using the default Shelf Life) and the Shelf Life check is using different logic. 
- The Shelf Life functionality on the Purchase Line is re-setting the user updated Expiration Dates back to the system calculated date. 
- There is a blank Description field on the SD-FB Item Shelf Life Worksheet Page. 
- Movements for Catch Weight Items received in are not being stamped to the SD-FB Item Unit Ledger table.





