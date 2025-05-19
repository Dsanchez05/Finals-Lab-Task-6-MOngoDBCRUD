# Finals-Lab-Task-6-MOngoDBCRUD
 
 In this task, we used MongoDB to create a database, insert and manage movie data, and perform queries and updates. We also practiced handling relationships using users, posts, and comments collections.

# Here are the Step-by-Step Process 
## create database
- use mongo_practice

## Insert Documents
- Insert the following documents into a `movies` collection.
  
![Screenshot 2025-05-19 205823](https://github.com/user-attachments/assets/09d9eae6-57fa-4a83-af14-a1b529a401f7)

![Screenshot 2025-05-19 205836](https://github.com/user-attachments/assets/7c4bdc99-98be-4894-86c4-6b0fc1f90a56)

![Screenshot 2025-05-19 205848](https://github.com/user-attachments/assets/0a9da83c-7030-4cfe-8c6a-57076ba04c34)

## Query / Find Documents
- Get all documents

![Screenshot 2025-05-19 210944](https://github.com/user-attachments/assets/7afc8c61-a8b8-4c1e-8282-8a1b983d93ac)

![Screenshot 2025-05-19 210955](https://github.com/user-attachments/assets/7ad41021-4904-4668-974e-75f13c3e8016)

![Screenshot 2025-05-19 211032](https://github.com/user-attachments/assets/5aceb473-21f5-45e2-9959-3f2c321a1b7a)

- Get all documents with `writer` set to "Quentin Tarantino"

![Screenshot 2025-05-19 211251](https://github.com/user-attachments/assets/4bbfb675-f92d-4ae0-a7a0-34a627c5b4cb)

- Get all documents where `actors` include "Brad Pitt"

![Screenshot 2025-05-19 211419](https://github.com/user-attachments/assets/a505d0e0-67cf-4e2d-8f9f-e0f0ec16f76e)

- Get all documents with `franchise` set to "The Hobbit"

![Screenshot 2025-05-19 211509](https://github.com/user-attachments/assets/5a183a2e-5949-4571-b3da-e686c19f7ae4)

- Get all movies released in the 90s

![Screenshot 2025-05-19 211608](https://github.com/user-attachments/assets/09c70f1b-5311-4bb9-a857-8dc57577dc52)

- Get all movies released before the year 2000 or after 2010

![Screenshot 2025-05-19 211716](https://github.com/user-attachments/assets/47791082-3a4f-4f87-b846-646b36851447)

## Update Documents
- Add a synopsis to "The Hobbit: An Unexpected Journey" : "A reluctant hobbit, Bilbo Baggins,
sets out to the Lonely Mountain with a spirited group of dwarves to reclaim their mountain home
and the gold within it - from the dragon Smaug."

![image](https://github.com/user-attachments/assets/514dc7fa-5aa7-4e68-a02d-045b567a3489)

- Add a synopsis to "The Hobbit: The Desolation of Smaug: : "The dwarves, along with Bilbo
Baggins and Gandalf the Grey, continue their quest to reclaim Erebor, their homeland, from
Smaug. Bilbo Baggins is in possession of a mysterious and magical ring."

![image](https://github.com/user-attachments/assets/a295c01d-b939-4a24-bc5f-b266ee9a5dfc)

- Add an actor named "Samuel L. Jackson" to the movie "Pulp Fiction"

![image](https://github.com/user-attachments/assets/20361984-6698-407f-acda-593c2dd74583)

## Text Search
- Find all movies that have a synopsis that contains the word "Bilbo"

![image](https://github.com/user-attachments/assets/8839b1ba-2cfa-4361-b179-c00976077ef0)

- Find all movies that have a synopsis that contains the word "Gandalf"

![image](https://github.com/user-attachments/assets/f128c760-797e-463e-bf9e-d06f55e24206)

- Find all movies that have a synopsis that contains the word "Bilbo" and not the word "Gandalf"

![image](https://github.com/user-attachments/assets/5926ab1d-a3da-4d51-9046-50a29055d14d)

- Find all movies that have a synopsis that contains the word "dwarves" or "hobbit"

![image](https://github.com/user-attachments/assets/d8906558-9cab-4c21-93c1-0489431b3360)

- Find all movies that have a synopsis that contains the word "gold" and "dragon"

![image](https://github.com/user-attachments/assets/f74feb5e-2602-4400-837c-1d87485ed7e9)

## Delete Documents
- Delete the movie "Pee Wee Herman's Big Adventure"

![image](https://github.com/user-attachments/assets/2ed4bd1f-09b2-4b29-995d-1902fd895755)

- Delete the movie "Avatar"

![image](https://github.com/user-attachments/assets/055afdde-32c7-403f-a5b6-6594b039516c)

## Relationships
- Insert the following documents into a `users` collection

![image](https://github.com/user-attachments/assets/acfc287e-6b0b-43bc-94a9-398ec4116425)

![image](https://github.com/user-attachments/assets/e517a79d-cd2f-4ba4-bb25-845a1868105d)

- Insert the following documents into a `posts` collection

![image](https://github.com/user-attachments/assets/13bff4f0-4aeb-4e02-b759-069af3703182)

- Insert the following documents into a `comments` collection

![image](https://github.com/user-attachments/assets/4f59a586-7791-454f-a4c8-a7571053c7d5)

## Querying related collections
- Find all users

![image](https://github.com/user-attachments/assets/97e0dbf0-cb15-4e82-bec2-bebeb7c9d081)

- Find all posts

![image](https://github.com/user-attachments/assets/a41a9fad-0b86-481f-bd9c-eb36aa4fa4e5)

![image](https://github.com/user-attachments/assets/7fc7b9f3-b326-413e-ae1c-286f41c1072a)

- Find all posts that was authored by "GoodGuyGreg"

![image](https://github.com/user-attachments/assets/957eb3b6-ea2f-40ff-97ae-db44e29f1388)

- Find all posts that was authored by "ScumbagSteve"

![image](https://github.com/user-attachments/assets/4508e9f0-e285-4acf-817b-c934d7be92dc)

- Find all comments

![image](https://github.com/user-attachments/assets/4479adb3-61f5-496a-9479-1d7b59771f57)

![image](https://github.com/user-attachments/assets/7b41632b-5645-4c37-8187-b8deef241086)

- Find all comments that was authored by "GoodGuyGreg"

![image](https://github.com/user-attachments/assets/2b5ebf05-4057-4e2e-8d2e-6dd9b85a90a7)

- Find all comments that was authored by "ScumbagSteve"

![image](https://github.com/user-attachments/assets/ab4047b7-d6ed-4c6f-8cdc-6d3b366d2846)

- Find all comments belonging to the post "Reports a bug in your code"

![image](https://github.com/user-attachments/assets/e02a54be-b379-457d-9cff-a51b417625a4)
