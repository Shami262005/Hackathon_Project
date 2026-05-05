# Hackathon_Project

Project name: Study Tracker


Study Tracker is a database that stores information on students’ study times and progress. It was created using MongoDB. It has 7 collections: Students, Courses, Enrolments, Chapters, Topics, Notes, and Sessions. Study Tracker makes it easier for students to track how long they take to finish a topic, and it keeps their topic notes in one location. Due to a time crunch, we didn't build a front end for our hackathon project.


Queries used
db.students.find()
db.students.updateOne({fullname: "Marlene Ntelamo"},
                  	{$inc: {cohort: 1}})
db.students.updateOne({hobbies: "cooking, drawing"}
db.students.deleteOne({hobbies: "cooking"}) 

Team Members
Halima Tambala
Lusia Kaushiningwa
Marlene Ntelamo
Shamiso Vushe
