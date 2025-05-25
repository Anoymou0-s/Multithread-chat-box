Multithreaded Chatbox in Java

Steps to run:

1. Compile the files:
   javac src/server/*.java src/client/*.java

2. Start the server:
   java -cp src server.ChatServer

3. Open new terminals to run multiple clients:
   java -cp src client.ChatClient

Database:
- chat_schema.sql: Creates a simple users table
- sample_data.sql: Inserts sample users
