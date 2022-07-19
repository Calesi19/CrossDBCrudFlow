# Overview


This program is CRUD (CREATE, READ, UPDATE and DELETE) interface I made for some noSQL databases. The program allows you to enter data into a database, as well as read from it, update it, and delete from it.

There are three different databases connected and the user is able to switch out at any moment which database they are manipulating.

I made this program to familiarize myself with how noSQL databases work.

In the following link, you can find a short video demonstration of the program.

[Software Demo Video](https://youtu.be/y8pfxCFzHF4)

# Cloud Database

For this program, I'm using Amazon's DynamoDB, Google's Firestore, and MongoDB as my databases.

Each of the databases have their own class. Each class has constructors that import all the necessary libraries and establish the connection with the databases. Each class has methods that allow the user to perform some basic databases like creating, reading, updating, and deleting entries. All of the database classes use the same method names so that Polymorphism can be applied.

# Development Environment

I used Visual Studio Code as my IDE for this program and Python 3.9 as my languange.

The following are the libraries that are being used in the program:
* pymongo
* MongoClient
* pprint
* certifi
* constants
* firebase_admin
* boto3
* requests

# Useful Websites

The following are some resources that were useful when creating this project:
* [Firestore Documentation](https://firebase.google.com/docs/firestore/quickstart)
* [MongoDB Documentation](https://www.mongodb.com/docs/)
* [DynamoDB Documentation](https://docs.aws.amazon.com/dynamodb/?id=docs_gateway)
* [Firebase vs MongoDB](https://www.youtube.com/watch?v=f49B0Ez8JkQ)
* [SQL vs NoSQL](https://www.youtube.com/watch?v=t0GlGbtMTio)
* [Choosing the best database for your project](https://www.youtube.com/watch?v=cODCpXtPHbQ)


# Future Work

Some features that can be added in the future are the following:
* More NoSQL Databases
* SQL Databases