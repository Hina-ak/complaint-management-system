# complaint-management-system
python-django-CSS,HTML project
About Complaint Management System Django Project
In particular, this complaint management system project in Python Django focuses mainly on dealing with user complaints. Also, the system displays selective overall data using graphical representations. In addition, the system allows for managing unsolved complaint records. Evidently, this project contains an Admin Panel with an employee and student panel. In an overview of this web application, a student can simply register themselves in order to use the features(codeastro.com). A student can submit complaints by filling up the subject with the type of complaint and description of it. The subject can be anything, but the user has to select any of the available complaint types. By default, the system contains a classroom, teacher, and management as types of complaints for this project. The students can also view their pending/unsolved complaints as well as their solved complaints. With it, the user can download the complaint details in pdf format.
While using the features of this complaint management system, the user can view all the statuses of registered complaints. For this, the system uses three different colors to indicate the current status. The red color is used to display the pending state whereas yellow and green are used for in-progress and solved status. And this goes the same with all other user levels; both employee and administrator. Also, a user can submit more than one complaint with the same type(codeastro.com). Besides, the students can view and update their profile details. Along with it, the users can also submit to reset their password details.

Instructions: How to Run?
After you finish downloading the project, unzip the project file and head over to the project root folder.
You can also create a Virtual Environment and Activate it.
Open your Terminal/Command Prompt on the project’s root folder.
Install the Requirements: pip install -r requirements.txt.
Create a [PostgreSQL] database named “complaintmsdjango”.
Configure PostgreSQL Database credentials under settings.py
Then, make database migrations: python manage.py makemigrations
python manage.py migrate
And finally, after a successful migration run the application: python manage.py runserver
At last, open up your favorite web browser
Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“
For the Admin Login credentials, you have to create one using superuser.
