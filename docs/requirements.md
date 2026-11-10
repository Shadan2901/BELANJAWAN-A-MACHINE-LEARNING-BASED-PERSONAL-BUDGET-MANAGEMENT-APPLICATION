# Requirements

## Functional requirements (what the system must DO)

1. The system shall allow users to create an account and sign in to access their private workspace.
2. The system shall allow users to add, edit and delete income records, including the amount, date and income source.
3. The system shall allow users to add, edit and delete expense records, including the amount, date, category and description.
4. The system shall allow users to set an overall monthly budget and display their monthly income, total expenses and remaining balance.
5. The system shall generate monthly expense reports with category-based charts, allow users to track savings goals, and analyse historical expenses to identify recurring patterns and estimate next month's expenses when sufficient records are available.

## Non-functional requirements (how the system must PERFORM)

1. The system shall load monthly summaries and expense reports within **3 seconds** when processing up to 5,000 financial records in the defined test environment.
2. The system shall protect users' financial information by ensuring users can only access their own records, storing passwords using secure hashing and using HTTPS for communication.
3. The system shall allow a first-time user to save a standard expense in no more than **4 actions** after opening the expense entry form.
4. The system shall successfully save at least **99 out of 100 valid transaction save attempts** and ensure saved records remain available after users sign out and sign in again.