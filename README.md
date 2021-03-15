# ListViewComponent

Preparation:
 Set Organization Wide Default of the Account object to Private.
 Create a custom profile with Create, Read & Edit access to the Account object. Assign a user to
this custom profile.
Challenge:
Develop a custom Lightning component using LWC (preferable, otherwise Aura framework) that
provides the following functionality:
 A lightning component should display a list of Account records which meets the following
criteria: Industry ="Financial Services" (Note: Add the “Financial Services” picklist value to
Industry field in the Account object). The heading of the component should read as ‘Financial
Services Account Listing’
 The list should include the following information for each account record: Account Name,
Account Owner, Phone, Website, and Annual Revenue.
 Ability to sort the data either by Account Name or Account Owner.
 Ability to filter the data based on Account Name using user input.
 Ability to edit a record directly in the component if user has permission to edit that record.
 Ability to navigate to the Account detail record page when user clicks the Account Name. The
record should be opened in a new tab. 

