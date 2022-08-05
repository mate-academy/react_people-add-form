# React People Table (Add form)
Implement the ability to add, edit and delete people saving the changes locally.

1. Create a `PersonForm` component with a form to add new people and show it above the table
    - all the fields should be required for now
    - `sex` should be chosen among 2 options (radio buttons)
    - `mother` and `father` are selects with all the `women` and `men` from the table accordingly
1. Create an `Add person` button
    - the `NewPerson` should appear instead of a button
    - When the person is added you should navigate back to the `/people` page
1. Add data validations:
    - `name` should contain only letters and spaces
    - `born` and `died` are valid years between `1500` and the current year
    - `died` should be disabled if `born` is empty
    - `died - born` should be >= 0 and < 150
    - make `mother` and `father` field optional
    - update the list of `mothers` and `fathers` according to the entered `born` year (they must be alive)
    (selects should be empty and disabled before the born year was entered)
1. Delete button should delete a person
1. Edit button should the Person for in the raw with save and cancel buttons
