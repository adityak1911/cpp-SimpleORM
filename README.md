# SimpleORM - A Lightweight C++ ORM

## Backstory

While working on a project where I was specifically instructed *not* to use any existing framework and instead build everything from scratch, I thought: why not make my own lightweight framework? My goal was to create something simple and easy to use, that wouldn't look or feel much like a typical framework.

As I explored the essential features of a framework, I stumbled upon **Object-Relational Mappers (ORMs)**. ORMs play a crucial role in handling database interactions, abstracting SQL queries to make code more readable and maintainable.

Initially, I planned to build this framework in PHP. However, as my mid-semester exams for the 5th semester approached and OOP concepts in C++ were part of my course, I thought, why not try building an ORM in C++ first? This allowed me to sharpen my C++ skills while working on something practical and reusable.

And that's how SimpleORM was born—a simple, lightweight ORM in C++ designed to generate SQL queries with ease.

## Project Description

SimpleORM is a C++ Object-Relational Mapper (ORM) designed to help developers easily generate SQL queries directly from C++ code. By eliminating the need to manually write SQL statements, it simplifies interaction with relational databases while maintaining strong type safety and performance.

### Features:
- **SQL Query Generation**: Automatically generate common SQL queries (SELECT, INSERT, UPDATE, DELETE) from C++ classes.
- **Custom Queries**: Flexibility to modify and fine-tune generated SQL queries with custom conditions.
- **Cross-Platform**: Works across different platforms supporting C++.

