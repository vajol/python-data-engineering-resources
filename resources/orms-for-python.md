# ORMs for Python

[Home](../README.md#python-data-engineering-resources)

## Table of Contents

1. [Introduction](#introduction)
2. [List of ORMs](#list-of-orms)
3. [Most popular ORMs](#most-popular-orms)
4. [How to choose ORM?](#how-to-choose-orm)

## Introduction

Object-Relational Mapping (ORM) in Python is a programming technique used to convert data between incompatible type systems in object-oriented programming languages and relational databases. ORMs in Python allow developers to interact with a database using Pythonic objects instead of writing SQL queries. This abstraction facilitates data manipulation and management, making database operations more intuitive and integrated within the Python code.

ORMs serve as a bridge between the Python code and the database, enabling developers to perform CRUD (Create, Read, Update, Delete) operations on the database without having to write verbose SQL syntax. This not only speeds up the development process but also enhances code readability and maintainability. By using ORMs, developers can focus more on the business logic of the application rather than the details of database interaction.

## List of ORMs

Here's a list of some popular Object-Relational Mapping (ORM) libraries for Python, along with links to their main resources and a brief description of each:

1. **SQLAlchemy**

   - **Website**: [https://www.sqlalchemy.org/](https://www.sqlalchemy.org/)
   - **Description**: SQLAlchemy is one of the most widely used ORM libraries in the Python community. It provides a full suite of well-known enterprise-level persistence patterns and is designed for efficient and high-performing database access.

2. **Django ORM**

   - **Website**: [https://docs.djangoproject.com/en/stable/topics/db/models/](https://docs.djangoproject.com/en/stable/topics/db/models/)
   - **Description**: Django ORM is part of the Django web framework. It allows you to define your data models entirely in Python and provides a powerful abstraction layer to translate your Python code to SQL.

3. **Peewee**

   - **Website**: [http://docs.peewee-orm.com/en/latest/](http://docs.peewee-orm.com/en/latest/)
   - **Description**: Peewee is a small, expressive ORM that provides a simple and intuitive interface to interact with the database. It's lightweight and designed to be easy to use, making it a great choice for small to medium-sized applications.

4. **Pony ORM**

   - **Website**: [https://ponyorm.org/](https://ponyorm.org/)
   - **Description**: Pony ORM is a unique ORM that uses generator expressions to define queries. It's designed to be intuitive and user-friendly, allowing for complex queries to be written in pure Python, closely mirroring human language.

5. **SQLObject**

   - **Website**: [http://www.sqlobject.org/](http://www.sqlobject.org/)
   - **Description**: SQLObject is a popular ORM that provides an object-oriented interface to your database, with tables as classes and rows as instances. It supports a variety of database backends and is designed for simplicity and ease of use.

6. **Tortoise ORM**

   - **Website**: [https://tortoise.github.io/](https://tortoise.github.io/)
   - **Description**: Tortoise ORM is an easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django. It's designed to be used with async and await syntax of Python, making it a great choice for asynchronous applications.

7. **ORM**

   - **Website**: [https://github.com/encode/orm](https://github.com/encode/orm)
   - **Description**: The ORM library is a lightweight and async-ready ORM that is designed to work with FastAPI and Starlette. It's particularly suited for applications that require asynchronous database operations.

8. **Gino**
   - **Website**: [https://python-gino.org/](https://python-gino.org/)
   - **Description**: Gino is an async ORM built on SQLAlchemy core. It's designed for async programming with asyncio and provides a simple and intuitive API for interacting with the database asynchronously.

These ORMs cover a wide range of use cases, from simple and lightweight libraries to more robust and feature-rich solutions, providing various options depending on the requirements of your Python project.

## Most popular ORMs

As of early 2024, several Python ORMs remain popular and actively used within the developer community. Here's a brief overview of some of the most notable ones:

1. **SQLAlchemy**: Widely regarded for its "just right" level of abstraction, making complex database queries easier compared to other ORMs [source](https://www.fullstackpython.com/object-relational-mappers-orms.html)

2. **Django ORM**: Integrated with the Django web framework, it works well for a variety of database operations but can be complex for more advanced queries.

3. **Peewee**: Known for being simpler and more hackable than SQLAlchemy, aiming for ease of use and readability.

These ORMs vary in their design philosophies, ease of use, and specific features, catering to different types of projects and developer preferences. Whether you need synchronous or asynchronous operations, a simple interface, or deep customization, there's likely a Python ORM that fits the bill.

## How to choose ORM?

When deciding among the three most popular Python ORMs—SQLAlchemy, Django ORM, and Peewee—your choice should depend on your project's specific needs and context. Here's a general guide on when to choose each:

1. **SQLAlchemy**:

   - Choose SQLAlchemy when you need a powerful, flexible ORM that can handle complex queries and supports a wide variety of database backends. It's a great choice if you want the flexibility to drop down to raw SQL when necessary and prefer a data-mapper pattern over active record.
   - It's ideal for applications where the database is a central component and requires sophisticated interactions and transformations.
   - SQLAlchemy is well-suited for both small-scale and enterprise-level applications due to its scalability and comprehensive feature set.

2. **Django ORM**:

   - Opt for Django ORM if you're already using the Django framework for your web application. Since it's tightly integrated with Django, it offers a seamless development experience within this ecosystem.
   - Django ORM simplifies the process of performing common web application tasks, making it a good choice for developers who prefer convention over configuration.
   - It's particularly well-suited for rapid development and applications where the database interactions are relatively straightforward or of moderate complexity.

3. **Peewee**:
   - Peewee is an excellent choice for smaller applications or when you prefer a lightweight, easy-to-learn ORM. Its simple and intuitive interface is great for quick development cycles and smaller codebases.
   - If you're working on a project where you don't need the extensive features of larger ORMs like SQLAlchemy and prefer a more straightforward, less verbose ORM, Peewee is a strong candidate.
   - It's particularly appealing for developers who prioritize readability and simplicity in their code and don't require advanced features like those offered by SQLAlchemy.

In summary, if you need a powerful and flexible ORM for complex applications, go with SQLAlchemy. If you're working within the Django ecosystem and want tight integration with your web framework, choose Django ORM. And if you prefer simplicity and are working on a smaller project, Peewee might be the best fit. Your specific project requirements, including the complexity of database interactions, the size of your application, and your development environment, will ultimately guide your choice among these ORMs.

---

[Back To Top](#introduction)
