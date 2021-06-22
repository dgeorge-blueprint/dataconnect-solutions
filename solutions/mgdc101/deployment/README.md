###MGDC101
This folder contains the arm templates of the pipelines that:
- extract the users and emails information from M365
- flatten the email objects using the 'ToRecipients', 'CcRecipients' and 'BccRecipients' fields
- join the users and emails
- insert the resulted join into a table from a dedicated synapse SQL pool 

The datasest and linked services templates are included along with the pipeline templates. 
