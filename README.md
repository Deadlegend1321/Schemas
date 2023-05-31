**Database Schemas:**

__Movies Schema Design:__

We’re going to design a movies database. Each movie has a title and year, one (and only one) director, and some number of actors. Actors can star in multiple movies. Directors can direct multiple movies. Some movies have the same title such as Ocean’s Eleven (the 2001 version directed by Steven Sodenbergh had George Clooney, Brad Pitt, Matt Damon, Julia Roberts, and many others, but the 1960 version was directed by Lewis Milestone and starred Frank Sinatra, Dean Martin and Sammy Davis Jr).


**Design Netflix Schema:**

Netflix has users

Every user has an email and a password

Users can create profiles to have separate independent environments.

Each profile has a name and a type. Type can be KID or ADULT.

There are multiple videos on Netflix.

For each video, there will be a title, description and a cast.

A cast is a list of actors who were a part of the video. For each actor, we need to know their name and list of videos they were a part of.

For every video, for any profile who watched that video, we need to know the status (COMPLETED/ IN PROGRESS).

For every profile for whom a video is in progress, we want to know their last watch timestamp.

__Design Online Classes Schema:__

System requirements:

1. Students can register for different batches (Ex: Feb’20)

2. Students attend daily lectures on various topics (like, Trees, Linked lists, stacks etc.)

3. Every lecture has an assignment and homework.

4. Every assignment and homework can have 0-10 problems.

5. Every class has an instructor, some prelecture content and lecture notes.

6. Students should be able to see the class timeline, problem solve percentage, attendance percentage and status of all the problems in all the assignments/homework in the dashboard.

7. Instructors should be able to see a list of classes taken by him and his upcoming class.

8. Instructors should be able to create lessons for all the batches and should be able to add and modify the assignments and homework problems.

Future Scope:

1. Store ratings and feedback or the class.

2. Collaborative lectures taken by multiple instructors.

3. Daily Streak calculation.
