# Phase 3 Syllabus: Flex Program, 60 Week Pace

## Learning Objectives

Welcome to Phase 3! At this point in the program, you've mastered the frontend:
you've gained proficiency in one language, JavaScript, and can use React to make
single-page applications that access data from an API (either on a server that
someone else runs, or on your own `json-server`). You can officially call
yourself a frontend developer! 🎉

By now, you've likely felt the limitation of what you can build without having a
real backend. Fear not! This is the point in the program when that all changes,
and you become **full-stack** developers.

In this phase, you'll learn a new language, **Ruby**, which has some
similarities to JavaScript as well as its own set of unique features that make
it a much beloved language. You'll also learn how to use Ruby to interact with a
**SQL database** where you can control how data is persisted. With those tools,
you'll be able to build out your very own simple backend **API** so that your
next project can take advantage of all the benefits of full-stack development.

By the end of the phase, you will be able to:

- Understand the fundamentals of Ruby as a language, including principles of
  object oriented programming
- Understand the characteristics of a relational database
- Perform CRUD (Create Read Update Delete) actions with a database via an
  Object-Relational Mapper
- Design an API to handle CRUD actions
- Communicate with an API using different HTTP verbs

Use the schedule below to make sure you're working through the material at
the right pace. The lessons marked with a ⭐️ are **milestones** that are useful
to check your understanding of the material you've learned. If you feel you're
falling behind, make sure to communicate with your instructor.

## Week 25 - 27

This week is all about learning the fundamentals of Ruby as a language.
Transitioning from one language to another is an important skill to have as a
developer (it's entirely possible your first job after Flatiron will require you
to learn a new language as well), so use this time to get to know and love Ruby.

You should be familiar with all the concepts from this week after having seen
them in JavaScript, so focus on the **syntax** and what makes Ruby unique.

**Note**: While there are a lot of lessons this week, don't feel obligated to
complete every single one. Make sure to review the lessons from each section and
familiarize yourself with the new syntax, but since there's a lot of material in
this phase, it's ok to skip some of the lessons and move ahead.

**Total Assignments: (74)**

- Procedural Ruby: Variables and Methods (13)
- Procedural Ruby: Booleans (3)
  - ⭐️ Truthiness Quiz
- Procedural Ruby: Logic and Conditionals (7)
  - ⭐️ Logic and Conditionals Quiz
- Procedural Ruby: Looping (8)
  - ⭐️ Looping Quiz
- Procedural Ruby: Arrays (5)
- Procedural Ruby: Iteration (15)
  - ⭐️ Enumerators Quiz
- Procedural Ruby: Hashes (11)
- Procedural Ruby: Working with Data Structures (14)
  - ⭐️ Iterating Over Hashes - Apples and Holidays Lab

## Week 28 - 30

Ruby is at its core a language for **object-oriented programming**. You've seen
some concepts related to object orientation in Phase 1 in JavaScript; in this
phase, you'll explore those concepts in more depth. You also may find that Ruby
also makes writing object-oriented code more pleasant than JavaScript.

Make sure to take your time with the concepts here, and ask for help if anything
isn't clear. Mastering Ruby means building a solid understanding of
object-oriented programming, so the concepts here are key to your ability to
gain proficiency in the material later in this phase and the next.

**Total Assignments: (77)**

- Introduction to Object-Orientation in Ruby (13)
  - ⭐️ Object-Orientation Fundamentals Quiz
- Topics in OO - Principles of Object Orientation (2)
- Topics in OO - Self in Ruby (7)
  - ⭐️ Self Quiz
- Topics in OO - Class Variables and Methods in Ruby (7)
  - ⭐️ Class Variables and Methods Quiz
- Topics in OO - Advanced Class Methods in Ruby (8)
  - ⭐️ Advanced Class Methods Quiz
- Topics in OO - Object Relationships in Ruby (15)
  - ⭐️ Object Relationships Quiz
- Topics in OO - Object Inheritance in Ruby (9)
- (Optional) Regex (4)
- Metaprogramming in Ruby (8)
  - ⭐️ Mass Assignment Quiz
- Configuring Ruby Applications (4)

## Week 31 - 33

With those Ruby skills under your belt, it's time to start learning the tools of
the trade for a backend developer: working with databases, and setting up a
server. You'll start with the fundamentals of SQL to learn how **relational
databases** work and how to model complex data. Then you'll learn how to use a
library, **Active Record**, to make it easy to work with databases in Ruby
applications. Finally, you'll learn how to set up a simple server using **Rack**
to handle requests, access/update data in the database, and send a response that
you can use on the frontend.

There's a lot of material here, so to help prioritize: the concepts in SQL and
Object-Relational Mapping (ORM) are important to know, but you won't end up
writing much SQL or ORM code yourself once you learn Active Record. If you find
those sections are slowing you down, talk with your instructor to help
prioritize, and focus on the readings over the labs from those sections.

**Note for students taking the code challenge**: the assessment will cover all
the material before **Rack**. It's recommended that you take the code challenge
after completing the Active Record Associations section.

**Total Assignments: (79)**

- Getting Started with SQL (14)
- Table Relations in SQL (10)
  - ⭐️ Table Relations in SQL Quiz
- Object-Relational Mapping (19)
  - ⭐️ Object-Relational Mapping Quiz
- Using Active Record (11)
  - ⭐️ Using Active Record Quiz
- Active Record Associations (9)
  - ⭐️ Active Record Associations Quiz
- Additional Practice: Active Record (4)
- Rack (11)
  - ⭐️ Rack and the Internet Quiz
- Rack and React - Practice Labs (1)

## Week 34 - 36

The time has come for your first full-stack project! In this phase, you'll be
building out a React frontend application once more, but you'll also have
control over the backend by creating your own server using Rack that can handle
requests from the frontend; communicate with the database using Active Record;
and send a response in JSON for the frontend to handle.

Details for the project can be found in the Milestones module.
