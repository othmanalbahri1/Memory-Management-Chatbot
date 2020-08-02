# CPPND: Memory Management Chatbot

This is my solution to Udacity's [Memory Management Chatbot](https://github.com/udacity/CppND-Memory-Management-Chatbot) project as part of the [C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213) as part of the Memory Management course.

<img src="images/chatbot_demo.gif"/>

The project implements:
- Various resource ownership policies.
- The Rule of Five.


The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file, a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer. The code is fully functional as-is and uses raw pointers to represent the knowledge graph and interconnections between objects throughout the project.

In this project you will analyze and modify the program. Although the program can be executed and works as intended, no advanced concepts as discussed in this course have been used; there are currently no smart pointers, no move semantics and not much thought has been given to ownership or memory allocation.

Your goal is to use the course knowledge to optimize the ChatBot program from a memory management perspective. There are a total of five specific tasks to be completed, which are detailed below.

## Dependencies and Basic Build Instructions

For more deails, please refer to the [original repository](https://github.com/udacity/CppND-Memory-Management-Chatbot).
