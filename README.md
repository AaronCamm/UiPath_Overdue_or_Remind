# UiPath Process for Processing CSV Files for Overdue Payments

### 1. Opens dialog so user can select CSV file
### 2. Loads CSV to a Data Table
### 3. Loops through each Row in Data Table
### 4. Checks if Column 4 in each Row is parsable to DateTime
### 5. If it is, then it finds the total days between today and the payment date
### 6. If it is less than 30 days then it sends a reminder email to the client of an upcoming payment
### 7. If it is more than 30 days then it sends an overdue notice via email to the client
