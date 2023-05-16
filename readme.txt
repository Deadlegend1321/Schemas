Schemas:

Movies Schema Design:
We’re going to design a movies database. Each movie has a title and year, one (and only one) director, and some number of actors. Actors can star in multiple movies. Directors can direct multiple movies. Some movies have the same title such as Ocean’s Eleven (the 2001 version directed by Steven Sodenbergh had George Clooney, Brad Pitt, Matt Damon, Julia Roberts, and many others, but the 1960 version was directed by Lewis Milestone and starred Frank Sinatra, Dean Martin and Sammy Davis Jr).

Design Netflix Schema:
Use Case
Netflix has users
Every user has an email and a password
Users can create profiles to have separate independent environments.
Each profile has a name and a type. Type can be KID or ADULT.
There are multiple videos on Netflix.
For each video, there will be a title, description and a cast.
A cast is a list of actors who were a part of the video. For each actor, we need to know their name and list of videos they were a part of.
For every video, for any profile who watched that video, we need to know the status (COMPLETED/ IN PROGRESS).
For every profile for whom a video is in progress, we want to know their last watch timestamp.
