####Note:- run `python manage.py migrate --run-syncdb` when running the app for first time.####

## Task Manager is made with Django without using any pre-built third-party apps.

Requirements:-
* python 3.7
* django 2.x

Task manager provides clean UI and Functionality for Managing Tasks within a Team or Personal Use.

Features (Personal Tasks) :-
* Plan, Create Personal Tasks.
* Track all tasks belonging to the User. 
* User can comment on Tasks.
* Edit Tasks.
* Mark Tasks as complete.


Features (Team Tasks) :- 
*Authenticate the user
*Allow new users to sign up
*Allow existing users to sign in
*Allow only an authenticated user to create Task
*Allow creation of ‘Teams’
*Team creator should be able to add other Users to their Teams
*Only the Task Creator can edit Tasks that have been created by himself
*Other users from the same team can only view and comment on Tasks that were created by another User
*A User from another Team cannot view/edit/assign/comment on a Task of a different Team Member.
*Creator of Task should be able to assign the Task to one or more Users from his own Team
*In case Task Creator does not belong to a team, he himself will always be assigned to his own tasks.
*Tasks should have the Fields: Title, Description, Assignee, and Status (Planned, Inprogress, Done etc.)
*Each Task should have a comments section where all users in one Team can comment on the Task
*An authenticated User can comment on his own tasks (assigned to or created by him) as well as other Tasks of his Team members.
***