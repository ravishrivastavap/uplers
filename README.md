# uplers

●	Create a new git repository.
●	All changes should be committed progressively.
●	We should be able to differentiate commits based on your own written code and framework/plugins or any other code which is not written by you. So make different commits to differentiate them.
●	Your repository must have README file mentioning the instructions of how to install and run the project.
●	In the comment box, please provide the summary of your work in English. Write it the way as you are replying to Client.
●	Public repository URL should be provided


Instructions
●	Using Angular/ReactJS/VueJS in the frontend.
●	Use Bootstrap or similar framework as Frontend base. Allowed to use datatables.


Database
●	Laravel Auth with different Roles : Admin, Registered User, Guest
●	We need to store all Events with fields : Title, Description, Date, Categories (multiple assignable), Location 	(single selectable). All fields are required except categories.
●	Comments to Event are allowed by Admin and registered users.
●	On Installation, 5 dummy events should be created using Fake Data.


FrontEnd
●	/categories page		
○	Fields to show : Name, Events count		
○	Only Admin accessible and all CRUD operations.	
●	/locations page		
○	Fields to show : Name, Events count		
○	Only Admin accessible and all CRUD operations. Restrict 	admin to delete any location if it is assigned to any Event.
●	/events page	
○	Viewable for all	
○	Edit/Delete option only for Admin.	
○	Search by name and date. 			
○	Filter by Category and Locations
●	event/{slug} page		
○	Viewable for all		
○	Show All Events fields.		
○	Comments hierarchy.		
○	Comment Form to show only for Admin and Registered User.	




