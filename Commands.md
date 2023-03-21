These are all the commands that i am going to learn through this course:

1. mongosh : this is a basic command to enter into mongosh terminal, after running this command in any terminal you will get details about mongoDB if it is installed properly in your system and your command prompt will look like "test>"

2. show dbs : this command will return all the databases present in your mongoDB

3. use <database name> : this command will switch you to the database that you will enter

4. show collections : It will show you all the collections that are present in that database

Note: In mongoDB there two essential things , 1 Database 2 Collections, Collections are like tables inside a database like SQL, it just stores data and we can name it whatever we want.

5. use <database_name> : This command will also used to create a database, if name that you entered is already exists then it will switch it to that database or else it will create a new database for you

Note: After creating database you might not get displayed your database when you run command :> show dbs , it is because you need to enter atleast one document into the database to display it.

6. db.<collection_name>.insertMany([{"key":"value"},{"key":"value"}]): This command will add multiple the object
   inside the collection of your database
   db.db.<collection_name>.insertOne({"key":"value"}) : Run this command if you want to insert only one object or file

7. db.dropDatabase(): If you run this command inside any database then that database will get deleted

8. cls : if you want to clear your terminal then run this command

9. exit: if you want to get out of mongosh terminal then run this command

10. db.<collection_name>.find() : This command will display all your files or objects present inside that collection

11. db.test.find().limit(x) : This command will return only first x objects if present

12. db.test.find().sort({"key":"value"}): This command will display the returned objects in sorted order, we can also sort objects by multiple keys

13. db.test.find().sort({"key":"value"}).limit(x) : This command will limit the sorted returned objects, it will return only first x objects

14. db.test.find().skip(1).limit(2)

15. db.test.find({name:"Shiva"})

16. db.test.find({name:"Manav"}, {age:1})
    db.test.find({name:"Manav"}, {age:1,\_id:0}) // Remove \ if you run these commands
    db.test.find({name:"Manav"}, {\_id:0})

17. db.test.find({name:{$eq:"Shiva"}})

18. db.test.find({name:{$ne:"Shiva"}})

19. db.test.find({age:{$gt:13}})

20. db.test.find({age:{$lte:13}})
    db.test.find({age:{$lt:14}})

21. db.test.find({age:{$exists:true}})
    db.test.find({age:{$exists:false}})

22. db.users.find({age:{$gte:20,$lte:13}})

23. db.users.find({$and:[{age:20}]})
    db.users.find({$and:[{age:20},{name:"manav"}]})

24. db.test.find({$or:[{age:{$lte:14}},{name:"Manav"}]})

25. db.users.find({age:{$not:{$lte:13}} })

26. db.users.find({age:{$gt:13}} )

27.

28.

29.

30.
