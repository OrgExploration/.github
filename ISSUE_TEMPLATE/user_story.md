# User Story
As a **USER**
I want to **delete rounds I no longer need**
so that **I can keep my rounds log up to date.**

# Summary
From the "Rounds" table in "Rounds" mode, users can click on the garbage can ("delete") button in a row to delete the corresponding round. A dialog should appear to require the user to confirm the deletion before completing the operation. When a round is deleted, it no longer appears in the "Rounds" table and it is removed from `localStorage`.

# Acceptance Criteria
- [ ] When the user clicks on the garbage can icon in a round row, a "Confirm Round Deletion" dialog box appears.
- [ ] The "Confirm Round Deletion" dialog box asks the user: "Do you really want to delete that round?"
- [ ] The "Confirm Round Deletion" dialog box has two choice buttons: "No, Cancel" (the default), and "Yes, Delete Round"
- [ ] Clicking on the "No, Cancel" button dismisses the dialog box without performing further action
- [ ] Clicking on the "Yes, Delete Round" button dismisses the dialog box and deletes the round from the table and from `localStorage`
