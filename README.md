# ClubGear Share

A real-time equipment sharing platform designed for student clubs. 

## Evaluator Testing Guide
To see the full backend state-machine in action, please follow this loop:
1. **Student View:** Open the live link and click "Request Booking" on any available item.
2. **Check History:** Scroll to the bottom to see the request change to pending in the student's history.
3. **Admin View:** Click "Go to Admin Dashboard" in the top navigation bar.
4. **Approve:** Click approve on the pending request. 
5. **Observe the Lock:** Return to the Student View and notice the item's status is now "Checked-Out" and physically locked from other users requesting it. 
6. **Upload Inventory:** Go back to the Admin Dashboard, paste an image address (URL) into the green form, and upload a new piece of equipment to the live database.