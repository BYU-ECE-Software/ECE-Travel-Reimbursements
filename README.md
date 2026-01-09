# ECE-Travel-Reimbursements
Travel reimbursement internal organization tool requested by Amy Warnick

Things Amy wants this site to do, for Not Amy:
- Main screen is a data table dashboard that looks like the purchasing site; Following fields are on the dash: Status (Created, Sent to student, waiting for reimbursement, Done), Name, Travel Dates, Purpose of travel (usually just the name of a conference), Professor (sortable), Destination, Account number, and Spend Category (optional, editable).
- Each Travel entry would have a button to the edit modal, as well as a button to see the Spend Authorization Line Items (editable)
- Spend authorization line items would be key-value pairings in the create modal with each coming in a dollar amount & category pairing (the categories are fixed according to workday) so that should probably be a dropdown
- Amy would like the datatable to be orderable by status and date, and searchable!
- No receipts or any kind of S3 storage (hooray)
