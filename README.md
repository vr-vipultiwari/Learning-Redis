Q1. What is redis all about?

Ans:- Redis is a database that means we can use it for persisting information for any kind of app information like user accounts, blog posts, comments and so on.
       After storing information, we can then retrieve it later on by writing queries. Now, this behavior is similar to just about every other database out there.
       
Q2. How it's is different and why do we decide to use this over any other database?

Ans:- The answer is simple , It is incredibly fast. Redis can store and retrieve data extremely fast.  
      Redis is fast because of primarily three reasons below 
     
      All data stored in memory :
      ===========================
      
      Most databases store all their information between both the memory of a computer and a hard drive.
      Accessing data in memory is fast, but getting data that is stored on the hard disk is relatively slow.
      So Redis made a simple decision here, Rather than storing any information on hard disk, it keeps all the data in memory.
      Now there is a very clear downside to this approach. It means that by default, it can be challenging to work with a dataset that is larger than the amount
      of memory that your computer has. So, for example, if you have a dataset that is 100 gigabytes large, but your computer only has eight gigabytes of memory, that is not going to fit in memory.

      Data is organised in simple data structures: 
      ===========================================
      
      The second reason is that Redis stores all of its data or its data organize in simple data structures  like link lists, sorted sets, hash maps and so on.
      These different data structures have very well known and very well understood performance characteristics.


      Redis has simple feature set :
      =============================
      Other databases like say PostgreSQL or MySQL etc choose to layer on a feature upon feature to make it easier to use but all those feature comes with big performance penalities.Redis is takes a very 
      different approach. Rather than stuffing ton of different features into the database, it is kept very simple on purpose.

![image](https://github.com/user-attachments/assets/7a515eb3-a2ce-4a10-ac12-38ff83646eef)

![image](https://github.com/user-attachments/assets/bc053fd2-cf66-4cdf-944b-0f6f288677b9)

      
     So in order to use Redis, we have to understand how to fit our data into a limited space. We have to understand how to fit our data or organize it using these simple data structures and we have to understand 
     how to work ourselves around this limited feature sets.
      
    In order to interact with redis data base we use commands, Commands are simple strings that we send to our database to save or retrieve some information.
      
    
