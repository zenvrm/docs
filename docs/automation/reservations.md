# Reservations
The reservations page provides a consolidated view of reservations in the system.

![reservations](images/reservations_full.png)

## Top Bar
By default, the data displayed is based on all properties within the system. By click the :material-chevron-down: button at the top, you can filter on any given property and the dashboard will update data specifically for that property.

### Search Filter
Typing in the box with the :material-magnify: icon will filter on data in the reservation table similar to the inbox search filter. 

![top bar](images/reservations_top_bar.png)

![filter](images/reservations_filter.png)

![add](images/reservations_add.png)

## Search
This provides information about the next 4 upcoming reservations as well as any existing reservations that are checking out. Clicking on any given reservation will take you directly to the booking data.

![search](images/inbox_filter_words.png)

## Individual Conversations
Clicking on a single conversation will display the full messaging contents as well as provide different information if the conversation is linked to a reservation or task.

### Messaging Section
The messaging section includes the full conversation data, the ability to create and send a new message, and information about saved replied or linked tasks as available. In the bottom pane, you can create a message and click the :material-send: button to send the message.

![section_message](images/inbox_section_message.png)

#### Saved Replies
If you have automation template messages that apply, the "Saved Replies" section will allow you to click the :material-chevron-down: button and list existing messages. Clicking on a message will automatically populate the send a message section with the contents.  
**Note:** Sending a message from this section may cause duplicate messages if the automation for the message is configured as well.

![section_message](images/inbox_saved_replies.png)

#### Linked Task
The linked task is a reference to the task associated with the message. Clicking on the task will take you directly to the actual task item details.

### Metadata Section
The metadata section includes information about the reservation or task. Reservation data is included for non-confirmed reservations as well (inquiry or request status as an example).
![meta_reservation](images/inbox_metadata_reservation.png) ![meta_task](images/inbox_metadata_task.png)

#### Reservation Metadata
Reservation metadata includes basic information about the reservation.

- Guest information
- Source of reservation (Airbnb, VRBO, etc)
- Reservation ID - this can be clicked to bring you directly to the reservation
- Status (Confirmed, Inquiry, etc)
- Dates
- Property information

#### Task Metadata
Task metadata includes basic information about the tasks.

- Assigned staff member
- List of current/upcoming tasks (existing task listed)
- Task ID - this can be clicked to bring you directly to the task
- Task Status (new, closed, etc) 
- Start and End Date
- Assigned Property
