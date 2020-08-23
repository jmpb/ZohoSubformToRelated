# Copy Zoho subform records to a related list

Copying records entered in a Zoho form's subform to a related list everytime they change.

## Why

Whenever a subform is used in an entity's form the selected records from subform's lookup bear no relation to the main entity. For that relationship to be preserved, the records need to be added to a related list on the entity.

## What

This Zoho Deluge script can be run in an Automation workflow to add any records from the subform to a related list. It will first use the Zoho CRM API to delink existing records and then link the records from the subform.

### Usage

Replace the following with appropriate values depending on which modules, related lists and subforms you are using.

- MODULE_NAME
- SUBFORM_NAME
- RELATED_LIST_NAME

Then create an automation in Zoho CRM to run the custom function when your criteria are met (for example; when a record in your module is edited).