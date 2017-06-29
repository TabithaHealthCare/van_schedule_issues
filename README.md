# Tabitha Van Schedule
* Url: http://&lt;host&gt;:8080/appointments/
* Username: &lt;blank&gt;
* Password: &lt;Same as old van scheduler&gt;

# Compatibility View Settings
* You need to go to your IE Settings ->
Compatibility View Settings -> uncheck 'Display intranet sites in
Compatibility View'
  * If you do not, the menu on the right will not
work.

# Main Page
* By default, shows the first 20 records for the last month
  * To change this, click “Adjust Filter” from theright menu
* Each day has a thick black header
* Each two hour block has a thin horizontal separator
* Aide assisted trips are marked with a red cross
* Deleting is currently done through the ‘Edit’ link
  * Deleting is recoverable
* Create Schedule and Export are admin functions
  * *Note:* Export will delete the records it exports and should only be used by accounting

# Appointment Form Entry
* For Resident, Pickup, and Destination fields
  * You can click in the input and it will give you a select list of all known appropriate values for that field
  * You can begin typing in the input and it will filter the select list based on what you have typed
  * You can enter a completely custom value as well
  
##### New Appointments
* Created By is a required field
* If you enter more than 3 (currently) aide assisted trips in one time slot, you will get an error
  * This is to bring the situation to your attention
  * You are required to acknowledge the over-scheduling by clicking the checkbox and re-save to continue
  * In the future, over-scheduling will automatically email Ron

##### Editing Appointments
* Last Updated By is a required field
* If you update the aide assisted flag in a way that over-schedules the time slot you are required to acknowledge this in the
same way with a create
* If you wish to delete an appointment you may check the 'Deleted' box
  * Deleted By and Reason for Deletion are required if 'Deleted' is checked

# Show Appointments
* Simply shows a bit more information about the appointment than the main page
