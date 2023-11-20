Step 1: Update App.js

Move the display of finished and unfinished states from HabitList.js to App.js.
Develop two handling functions to signal a preference for either concealing or not displaying incomplete items in a user interface.
Send the props to the CategoryDropdown and habitList components.

Step 2: Modify the HabitList.js

Remove the state and related functions, and use the props instead.
Delete handleToggleUnfinished function.
Delete "Show Finished Habits" and "Show Unfinished Habits" buttons.
Update dependency in useEffect hook. 

Step3: Update CategoryDropdown Component

Create two new buttons: "Finished Habits" and 'Unfinished Habits'.
Remove the state and related functions, and use the props instead.




