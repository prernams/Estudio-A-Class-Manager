# Estudio-A-Class-Manager


Estudio is an organizer app that lets the admin create data and the users read
them. The class representative/ teacher logs in to the app using their
credentials (Create account as Teacher if not registered). Once they log in,
they can enter an already existing class or can create a class proving the class
name.
Once they create / enter a class, they are given the class code which they are
free to share with their students. The students login to the app using their
credentials(Create account as Student if not registered ). Once they login,
they are asked to enter the class code provided by their teacher/
representative. On the entering the code, are directed to the welcome page
where they can access the information they choose. Information regarding
their Assignments, Teachers (Staff), Announcements, Timetable.
The admin (teacher / representative) can logout whenever they wish to.
The interface is very convenient, comprehendible and friendly.
We have used Firebase Realtime Database, Firebase FireStore and Firebase
Authentication for the backend of this app. Firebase Authentication is used
to store the login ID with the hashed passwords. Firestore is used to store the
login/ account details like isTeacher/isStudent , the accounts’ current class
code etc. Realtime DB for storing information regarding Assignments,
Teachers and Timetable. Any data can in the DB can be modified only by
the admin (teachers).
Since our app uses Firebase as the backend, the app requires internet to
function.

