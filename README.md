# Spark-Scala-University-student-courses-teachers-Dataset

Create a new Dataframe named instructorTeachings that holds
the results of joining (using Spark SQL, if you'd like) the
instructors table to the teachings table.
The instructors table has an id field and the teachings table
has an instructor_id field.
Show() the results.

2) Create a new Dataframe named instructorTeachingCount that contains
a list of each instructors name and a count of the sections they
have taught.
Show() the results.

3) Create a new Dataframe
named teachingsByInstructorSorted and have it hold the data
from instructorTeachingCount sorted on both count in descending order
and then on instructor name so that the instructor who has taught the
highest count will be towards the top

1) Create a Scala variable that holds the row count from the
course_offerings table.
2) Do this with only one line of code.

Do it by loading the course_offerings table into a Dataframe and using
the count() method.

If you can do it using the Dataframe count() method, but can't get
it down to 1 line, you'll still get partial credit!

3) Use the println() function to printout the value in the variable
you created in step 1



1) Load the course_offerings table into a Dataframe called offerings.
2) Use the Dataframe functions (not Spark SQL) to create a new dataframe
called namesWithCount that contains a count of the times each offering
name occurs in the offerings Dataframe.

Show the first 10 rows of that Dataframe.

*** Check the exam 3 prep material for some pointers.
*** Look for groupBy() and related methods.

Your output should look very much like this:
+--------------------+--------+
|                name|count(1)|
+--------------------+--------+
|     Math for Tchng:|      13|
|Where Science Mee...|      13|


3) Use the Dataframe functions (not Spark SQL) to create a new Dataframe
called offeringCountSorted and have it contain the offering name and
offering count, as in step 2, but this time have it be ordered by name.
Use show() to dispay results.

Your results should look like this:
+--------------------+--------+
|                name|count(1)|
+--------------------+--------+
|"Scand Modern" Ph...|       1|
|17th C Literature...|       2|
|17th-Century Lite...|       1|

4) Use the Dataframe functions (not Spark SQL) to create a new
Dataframe named offeringsCountRenamed, with the same content as step 3,
but have the count column be named offeringsCount.
Use show() to display the results.

5) Use the Dataframe functions (not Spark SQL) to create a new
Dataframe named countRenamedAndOrdered that contains the same
content as step 4, but have it be ordered by offeringsCount.

Use show() to display the results.

Your output will be similar to this:
+--------------------+--------------+
|                name|offeringsCount|
+--------------------+--------------+
|"Scand Modern" Ph...|             1|
|17th C Literature...|             2|




1) Create a new Dataframe named instructorTeachings that holds
the results of joining (using Spark SQL, if you'd like) the
instructors table to the teachings table.
The instructors table has an id field and the teachings table
has an instructor_id field.
Show() the results.

2) Create a new Dataframe named instructorTeachingCount that contains
a list of each instructors name and a count of the sections they
have taught.
Show() the results.

3) Create a new Dataframe
named teachingsByInstructorSorted and have it hold the data
from instructorTeachingCount sorted on both count in descending order
and then on instructor name so that the instructor who has taught the
highest count will be towards the top.


