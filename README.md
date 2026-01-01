This project is an attempt to organize all the math I have learned throughout my undergraduate years.

It has two purposes:

  1. To create a knowledge base I can refer to whenever my understanding gets rusty.
  2. To build a database that even beginners can pick up and start reading.
     To do this, we aim to structure the database as a DAG,
     where each edge indicates a prerequisite dependency.

The plan is as follows:

  - Modularization: each `.md` file will be about the length of a small textbook section.
  - Dependency: Each `.md` file will be treated like a node in a DAG.
                Each node explicitly lists its prerequisites (e.g., in YAML front matter),
                so the dependency graph can be extracted automatically and checked for cycles.

Initially, I will use Obsidian to browse and edit the notes
and to explore connections via links and graph views.
In the future I may develop a front-end application that visualizes the dependencies exactly as I want.
