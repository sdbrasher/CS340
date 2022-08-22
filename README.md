# CS340
Repository for CS 340 - Client/Server Development

Modularity is an important concept in computer programming. It allows for adaptable code that is, potentially, easy to maintain. In the instance of this project, the CRUD module allows us to connect to a Mongo database with different usernames and passwords, and read different records in different collections. With minor changes (not hard-coding the port, for example), this module could be used in a variety of other instances.

As a computer scientist, I approach problems by thinking first of user goals. These goals can be translated into an accomplishable task, and that task can then be broken up into smaller tasks. One difference in my approach to this project was recognizing which of these smaller tasks are generalized and potentially repeatable (like reading a document from a database), and extracting that functionality to a separate module. I believe this approach helps tremendously in debugging and testing, as once I determined a particular portion of the code was working, I could rely on it in further project development.

Given that computers can accomplish a wide variety of tasks at an incredible rate of speed, creating meaningful programs that align with ethical user goals is an incredibly extrinsicly important task. In the example of this project, helping Grazioso Salvare find dogs for search and rescue purposes, we are helping them connect with better suited dogs in a more timely manner. While this software may not directly lead to a saved life, it is easy to see how it could lead to move lives saved when properly implemented.
