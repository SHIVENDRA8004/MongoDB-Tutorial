These are all the commands that i am going to learn through this course:

1. mongosh : this is a basic command to enter into mongosh terminal, after running this command in any terminal you will get details about mongoDB if it is installed properly in your system and your command prompt will look like "test>"

2. show dbs : this command will return all the databases present in your mongoDB

3. use <database name> : this command will switch you to the database that you will enter

4. show collections : It will show you all the collections that are present in that database

Note: In mongoDB there two essential things , 1 Database 2 Collections, Collections are like tables inside a database like SQL, it just stores data and we can name it whatever we want.

5. use <database_name> : This command will also used to create a database, if name that you entered is already exists then it will switch it to that database or else it will create a new database for you

Note: After creating database you might not get displayed your database when you run command :> show dbs , it is because you need to enter atleast one document into the database to display it.

6. db.<collection_name>.insert({"key":"value"}): This command will add the object inside the collection of your database

7. db.dropDatabase(): If you run this command inside any database then that database will get deleted

8. cls : if you want to clear your terminal then run this command
